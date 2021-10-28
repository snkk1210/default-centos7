zabbix-server
=========

## これは何？

zabbix-serverを導入するplaybookです。

- レポジトリインストール
- zabbix-serverインストール
- DBデプロイ
- zabbix-server設定

## Dependencies

- mysql-server*

## 変数

root_passworにMySQLのrootパスワードを定義  
zabbix_passwordにzabbixユーザ(MySQL)のパスワードを定義

```
root_password: W3mrzy4M:sgt
zabbix_password: gstshsW3mrzy4M:sgtsh
```

## 補足

/etc/my.cnfに下記を追記して下さい。

```
character_set_server=utf8mb4
```

License
-------

BSD

Author Information
------------------

- keisuke sanuki 
