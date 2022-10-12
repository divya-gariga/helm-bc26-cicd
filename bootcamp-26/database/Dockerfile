FROM mysql:latest 
ENV MYSQL_ROOT_PASSWORD root
ADD book_discovery.sql /docker-entrypoint-initdb.d
EXPOSE 3306