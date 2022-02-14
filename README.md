# FundastA 研修内容
## 未経験者用研修課題
### クラウドインフラとプログラムに慣れる
#### 課題内容
> ユーザ情報のバイナリデータを受け取りデータを永続保存し、そのデータを外部から時系列で参照可能にする
1. 条件1.以下のアーキテクチャを使用する
  - ユーザ情報転送側：HTTPS → Kinesis → Lambda → S3
  - 外部データ取得側：HTTPS → API Gateway (Custom Authorizer: Cognito) → Lambda → S3 → Response
1. 
