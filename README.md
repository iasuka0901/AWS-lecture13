## AWS-lecture13リポジトリ
Target NodeのEC2インスタンスにElastic IPを使用した固定IP構成です
## 概要
このリポジトリでは以下の自動化プロセスをCircleCIで実行します：
1. **CloudFormationの構文チェック**
2. **CloudFormationスタック実行**  
   - EC2、ALB、RDS、S3の作成を含むAWSインフラの構築
3. **Ansibleによる環境構築**
   - EC2インスタンス上でサンプルアプリケーションのセットアップ
4. **Serverspecでのテスト**  
   - EC2インスタンスの環境確認および動作テスト 
## 実行環境
Controle Node：CircleCI
Target Node：EC2(Amazon Linux2)

CircleCI実行結果はこちら：  
[CircleCI Execution Result](https://app.circleci.com/pipelines/github/iasuka0901/AWS-lecture13/29/workflows/8222ca97-29ee-4587-9dad-7fff75c83d53)