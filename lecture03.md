# 第3回課題
## サンプルアプリケーションの起動
![SampleApp](https://github.com/Masaki0412/ProblemManagement/blob/28e30ed415df8ef4466c79d77685a9275f3e61e2/image03/%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3_%E3%83%87%E3%83%97%E3%83%AD%E3%82%A4.png "SampleApp")

## APサーバーについて調べる
* APサーバーの名前とバージョンの確認
APサーバー：Amazon EC2
バージョン：4.14.320-242.534.amzn2.x86_64

* APサーバーを終了させた場合、引き続きアクセス可能か？
アクセス不可能
![APAccess](https://github.com/Masaki0412/ProblemManagement/blob/28e30ed415df8ef4466c79d77685a9275f3e61e2/image03/%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3_AP%E3%82%B5%E3%83%BC%E3%83%90_%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E7%A2%BA%E8%AA%8D.png "APAccess")

## DBサーバーについて調べる
* サンプルアプリケーションで使ったDBサーバー(DBエンジン)の名前
DBサーバー：MySQL

* 今、Cloud9で動作しているバージョン
バージョン：mysql Ver 8.0.34 for Linux on x86_64 (MySQL Community Server - GPL)

* DBサーバーを終了させた場合、引き続きアクセス可能か？
アクセス不可能
![DBAccess](https://github.com/Masaki0412/ProblemManagement/blob/28e30ed415df8ef4466c79d77685a9275f3e61e2/image03/%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3_DB%E3%82%B5%E3%83%BC%E3%83%90_%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E7%A2%BA%E8%AA%8D.png "DBAccess")

* Railsの構成管理ツールの名前
bundler

## 今回の課題から学んだこと
gitのmainブランチにサンプルアプリケーションをクローンしないと動作しないのではないかと考えていたが、それが間違いであること。
