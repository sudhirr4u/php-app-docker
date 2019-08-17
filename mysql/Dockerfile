FROM mysql:5.6

ADD ./dbtest.sql /docker-entrypoint-initdb.d

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=dbtest

EXPOSE 3306
