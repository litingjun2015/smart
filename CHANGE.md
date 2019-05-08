

# v1.0.0

基础系统建立

# local

## MySQL 8.0.16版本连接报错：Could not create connection to database server.

smart\pom.xml

```
<mysql.version>8.0.16</mysql.version>
```

## jdbc.properties

smart\smart-sso\smart-sso-server\deploy\dev\jdbc.properties

```
sys.driver = com.mysql.cj.jdbc.Driver
sys.url = jdbc:mysql://localhost:3306/smart-sso?serverTimezone=Asia/Shanghai&characterEncoding=utf8
sys.username = root
sys.password = ynca_0801
```