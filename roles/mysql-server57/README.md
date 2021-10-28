mysql-server57
=========

## これは何？

mysql5.7を導入し、初期設定まで行うplaybookです。

- レポジトリの追加
- my.cnf設定
- mysqlインストール
- expectインストール
- mysql再起動
- mysql初期設定(mysql_secure_installation)

## 変数

mysqlのパラメータを定義して下さい。

```
---
# vars file for db_backup
innodb_buffer_pool_size: 256M
key_buffer_size: 128M
```

mysqlのrootユーザのパスワードを定義して下さい。

```
vi ./files/mysql_secure_installation
====================================
#変更後のDBパスワードを設定
db_pass=aes7sChea7v:12
```

License
-------

BSD

Author Information
------------------

- keisuke sanuki 
