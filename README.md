# firewalld-config

firewalld-configはCentOS7やFedoraなどで使用されているfirewalldのユーザ定義サービスの設定ファイルをまとめました。

## 使い方

本リポジトリをクローンした後、/etc/firewalld/services以下に必要なファイルをコピーしてください。
```
git clone https://github.com/KuriharaJun/firewalld-config.git
cd /etc/firewalld/services
sudo cp ~/firewalld-config/services/xxx.xml
```

## ユーザ定義サービス設定ファイル

### 現在含まれているユーザ定義サービス

### 追加予定のユーザ定義サービス

- Microsoft SQL Server
- PostgreSQL
- MySQL
- MongoDB
- Redis
- Apache Tomcat

### License

本設定はすべて MIT License となっています。
