FROM mysql:9.4.0-oraclelinux9

ENV MYSQL_DATABASE test

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/
COPY home_rentals.csv /
