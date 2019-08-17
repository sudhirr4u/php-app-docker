FROM mysql:5.6

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=dbtest

ADD ./dbtest.sql /docker-entrypoint-initdb.d

EXPOSE 3306
