docker run -it -e MYSQL_USER=fmengoni -e MYSQL_PASSWORD=123456 -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_DATABASE=todos -v mysql-8.0.31-oracle:/var/lib/mysql -p 3306:3306 --name mysql mysql:8.0.31-oracle