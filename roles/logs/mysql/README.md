logs/mysql
=========

## これは何？

MySQL log のローテート設定を調整するplaybookです。

- /root/ 配下に .my.cnf を配置
- error / slowlog のログローテートを調整

## Dependencies

- mysql-serverxx

## 変数

interval_mysql に ログローテーション間隔を定義  
rotate_num_mysql に ログ保持期間を定義  
※ 変数を設定しなければ、デフォルト (下記) の設定になります。

```
interval_mysql: daily
rotate_num_mysql: 4
```

License
-------

BSD

Author Information
------------------

- keisuke sanuki 
