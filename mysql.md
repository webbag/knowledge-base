# MySQL

sudo mysql

SELECT user,authentication_string,plugin,host FROM mysql.user;

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

mysql -u root -p
CREATE DATABASE my_db;
SHOW TABLES FROM my_db;
SHOW DATABASES;

mysqldump -u user -p db_name > /home/file_name.sql
mysql -u user -p --database db_name < /home/file_name.sql 
