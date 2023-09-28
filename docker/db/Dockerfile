FROM mysql:5.7-debian
FROM mysql/mysql-server:5.7

COPY my.cnf /etc/mysql/conf.d/my.cnf

ENV TZ Asia/Tokyo

CMD ["mysqld"]

EXPOSE 3306