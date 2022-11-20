FROM registry.cn-hangzhou.aliyuncs.com/zqqq/mysql:8.0.30-arm

ADD nacos-mysql.sql /docker-entrypoint-initdb.d/nacos-mysql.sql

ENV MYSQL_ROOT_PASSWORD=root \
    MYSQL_DATABASE=nacos \
    MYSQL_USER=nacos \
    MYSQL_PASSWORD=nacos

EXPOSE 3306

VOLUME [ "/var/lib/mysql" ]