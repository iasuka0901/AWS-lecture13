## AWS-lecture13リポジトリ
Target NodeのEC2インスタンスにElastic IPを使用した固定IP構成
## 概要
本リポジトリでは以下の自動化プロセスをCircleCIで実行：
1. **CloudFormationの構文チェック**
2. **CloudFormationスタック実行**  
   - EC2、ALB、RDS、S3の作成を含むAWSインフラの構築
3. **Ansibleによる環境構築**
   - EC2インスタンス上でサンプルアプリケーションのセットアップ
4. **Serverspecでのテスト**  
   - EC2インスタンスの環境確認および動作テスト 
## 実行環境
- Controle Node：CircleCI<br>
- Target Node：EC2(Amazon Linux2)<br>

- CircleCI実行結果はこちら：<br>
[CircleCI Execution Result](https://app.circleci.com/pipelines/github/iasuka0901/AWS-lecture13/44/workflows/69b6fb4c-cdce-41ea-8529-16673e5dda22)