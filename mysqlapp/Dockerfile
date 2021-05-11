FROM mysql

LABEL taskmysql7 true

COPY . .

ENV MYSQL_USER user
ENV MYSQL_PASSWORD pass
ENV MYSQL_ROOT_PASSWORD pass
ENV MYSQL_DATABASE testtask

ADD test.sql /docker-entrypoint-initdb.d
