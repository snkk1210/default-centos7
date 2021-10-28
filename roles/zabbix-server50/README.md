zabbix-server
=========

## これは何？

zabbix-serverを導入するplaybookです。

- レポジトリインストール
- zabbix-serverインストール
- DBデプロイ
- zabbix-server設定

## 変数

db_passwd に MySQL の rootパスワードを定義  
zabbix_password に zabbixユーザ(MySQL)のパスワードを定義

```
db_passwd: W3mrzy4M:sgt
zabbix_password: gstshsW3mrzy4M:sgtsh
```

## 補足

/etc/my.cnfに下記を追記して下さい。

```
character_set_server=utf8
collation-server=utf8_bin
```

License
-------

BSD

Author Information
------------------

- keisuke sanuki 
