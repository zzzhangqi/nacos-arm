FROM registry.cn-hangzhou.aliyuncs.com/zqqq/nacos-server:v2.1.2-slim-arm

ENV PREFER_HOST_MODE=ip \
    MODE=standalone \
    SPRING_DATASOURCE_PLATFORM=mysql \
    MYSQL_SERVICE_HOST=127.0.0.1 \
    MYSQL_SERVICE_DB_NAME=nacos \
    MYSQL_SERVICE_PORT=3306 \
    MYSQL_SERVICE_USER=nacos \
    MYSQL_SERVICE_PASSWORD=nacos

EXPOSE 8848 9848 9849