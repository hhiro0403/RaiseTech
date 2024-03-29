# **第5回課題**

## 課題報告

### EC2上にサンプルアプリケーションをデプロイ
![a](./img5/a.png)

### サーバーアプリケーション（nginx + unicon)だけで動作確認

![b](./img5/b.png)


### ELB追加・動作確認

- ロードバランサー作成
![c](./img5/c.png)

- ターゲットグループ作成
![c1](./img5/c1.png)

- 動作確認

![c2](./img5/c2.png)

### S3作成

![d](./img5/d.png)

### EC2からS3にファイルを保存する

- EC2にS3にアクセスできるようにIAMロールを設定

![e](./img5/e.png)

- アプリケーションから画像の取り込み

![e1](./img5/e1.png)

- S3上で取り込めているかの確認

![e2](./img5/e2.png)
![e3](./img5/e3.png)

- EC2上でも取り込めているかの確認

![e4](./img5/e4.png)

### 構成図

![f](./img5/f.png)


### 今回の課題で学んだこと
- 課題5はこなすのに物凄く時間がかかりアプリケーションのデプロイするためのEC2の構築・動作確認など
- ハンズオンしなければ理解はできないことばかりだったと感じております。
- ELBの配置やS3を使ったデータの保存など奥深い課題で一つ一つ理解を得るためにも
- もっと自身で触っていくこと、細かくメモをとってある内容の深掘りなどよりしていけたらと思っております