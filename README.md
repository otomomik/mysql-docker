# MySQL Docker

複数バージョンのMySQLをDockerで起動可能

# 前提条件

- dockerのインストール（docker-composeも同様）

# 構成

- MySQL
  - 5.7
  - latest

# MySQLサーバーの起動

以下のコマンドを実行
```
make up
```

# MySQLサーバーの停止

```
make down
```
