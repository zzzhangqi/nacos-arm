FROM mysql:8.0.30

ADD nacos-mysql.sql /docker-entrypoint-initdb.d/nacos-mysql.sql

ENV MYSQL_ROOT_PASSWORD=root

EXPOSE 3306

VOLUME [ "/var/lib/mysql" ]