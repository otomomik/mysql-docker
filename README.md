# MySQL Docker

複数バージョンのMySQLをDockerで起動可能

# 前提条件

- dockerのインストール（docker-composeも同様）

# 構成

- MySQL
  - 5.7
  - 8.0
- phpMyAdmin
  - latest
※ phpMyAdminにアクセスする際は `.env` の`MYSQL_ROOT_PASSWORD` をパスワードとして使用する

# MySQLサーバーの起動

以下のコマンドを実行
```
sh start.sh
```

# MySQLサーバーの停止

```
sh stop.sh
```
