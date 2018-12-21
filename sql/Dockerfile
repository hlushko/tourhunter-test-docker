FROM mysql:8.0

COPY init.sql /docker-entrypoint-initdb.d/
COPY app.cnf /etc/mysql/conf.d/
