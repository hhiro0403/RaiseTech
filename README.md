# RaiseTech AWSコース

## 概要説明
- 2023/08 月より受講開始
- 下記のAWS環境を手動構築・手動で構築した内容をCloudFormationを利用して自動構築およびインフラコード化を支援するツールの使用（ServerSpec・CircleCI ）
![a](./lecture10/課題５で作成した構成図を元に環境を構築していく.png)

- 作成したファイルは[RaiseTechリポジトリ](https://github.com/hhiro0403/RaiseTech/blob/main/README.md)を参照

### 学習記録
 RaiseTechで学習した講座内容と課題は下記の通りになります。<br>
|講座|講義内容|課題|課題ファイル|備考|
|:---|:---|:---|:---|:---|
| 第 1 回  | ・最初に伝えておきたいこと<br>・なぜ AWS を扱うのか<br>・AWS とは<br>・クラウドインフラが変えたもの<br>・インフラエンジニアとは？<br>・インフラエンジニアとシステムの関わり<br>・開発環境の構築<br>・HelloWorld の実装<br>・AWS アカウントの作成 | ・AWS アカウントの作成<br>・IAM の推奨設定<br>・Cloud9 の作成 | <br>作成・設定のため課題ファイルは無し | - |
| 第 2 回  | ・バージョン管理システム<br>・Git<br>・Markdown<br>・チーム開発におけるバージョン管理<br>・開発で役立つ GitHub TIPS<br>・GitHub での PR 作成デモンストレーション | ・Git Hub アカウントの作成<br>・Git 設定変更<br>・Pull Request の練習<br>・課題用リポジトリ作成と設定変更<br>・Pull Request の発行と完了報告 | [lecture02.md](lecture02.md)  | - |
| 第 3 回  | ・Web アプリケーションとは<br>・Web アプリケーションでよく使う(見かける)言葉<br>・システム(アプリケーション)開発の流れ<br>・外部ライブラリと構成管理の重要性<br>・Gem と Bundler<br>・アプリケーションサーバー<br>・Rails による Web アプリケーションの起動<br>・DB と SQL | ・Cloud9 へサンプルアプリケーションをデプロイ<br>・AP サーバについて調べる<br>・DB サーバについて調べる | [lecture03.md](lecture03.md) | - |
| 第 4 回  | ・AWS 環境の完成イメージ<br>・AWS での権限管理<br>・VPC、サブネット構築<br>・EC2 インスタンスの作成<br>・RDS の作成 | ・VPC, EC2, RDS を作成<br>・EC2 から RDS へ接続 | [lecture04.md](lecture04.md)  | - |
| 第 5 回  | ・EC2 へアプリケーションをデプロイ<br>・ELB 経由で EC2 へ接続<br>・アプリケーションのデータ保存先を S3 に変更<br>・インフラ構成図を書く | ・EC2 へ サンプルアプリケーションをデプロイ<br>・構成に ELB を加える<br>・S3 を加え、画像データを S3 に保存させる<br>・draw.io で構成図を書く | [lecture05.md](lecture05.md) | - |
| 第 6 回  | ・システムの安定稼働<br>・AWS での証跡、ロギング<br>・「履歴がないこと」がどれだけ重大なのかを理解する<br>・AWS での監視、通知<br>・ALB のアラーム通知デモンストレーション<br>・AWS でのコスト管理 | ・自分が最後に利用した  CloudTrail のイベントから 3 つ抜き出す<br>・CloudWatch アラームを使って、ALB のアラームを設定して、メール通知させる<br>・AWS 利用料の見積を作成<br>・マネジメントコンソールから、現在の EC2 利用料を確認 | [lecture06.md](lecture06.md) | - |
| 第 7 回  | ・システムにおけるセキュリティの基礎<br>・セキュリティ対策計画の主体は誰が適切？<br>・AWS でのセキュリティ対策（脆弱性）<br>・AWS でのセキュリティ対策（認証情報の流出）<br>・AWS でのセキュリティ対策（人為的な過負荷）<br>・AWS でのセキュリティ対策（その他知っておくべきサービス） | なし | - | - |
| 第 8 回  | ・構築の実演（1） | なし | - | 講師による第 5 回目のライブコーディング |
| 第 9 回  | ・構築の実演（2） | なし | - | 講師による第 5 回目のライブコーディング |
| 第 10 回  | ・インフラ自動化<br>・自動化のメリット<br>・全自動と半自動<br>・自動化の範囲<br>・CloudFormation<br>・CloudFormation テンプレートの解説 | ・CloudFormation で現在までに作った環境をコード化 | [lecture10.md](lecture10.md) | - |
| 第 11 回  | ・インフラのコード化を支援するツール<br>・インフラのテストとは<br>・テスト駆動開発<br>・ServerSpec<br>・良い質問と回答ピックアップ | ・ServerSpec のテストを成功させること | [lecture11.md](lecture11.md) | - |
| 第 12 回  | ・Terraform の解説<br>・DevOps<br>・CI/CD ツールとは<br>・イベントトリガーの設定や連携<br>・閑話休題(良い質問と回答のピックアップ) | ・CircleCI のサンプルコンフィグが正しく動作するようにリポジトリに組み込む | [lecture12.md](lecture12.md) | - |