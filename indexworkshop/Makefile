MYSQL_ENDPOINT=127.0.0.1
MYSQL_SERVICE=sqlworkshop_workshop_mysql_1

mysql-login:
	mysql -h $(MYSQL_ENDPOINT) -u root -pPassw0rd
mysql-index:
	mysql -h $(MYSQL_ENDPOINT) -u root -pPassw0rd -t -e "source ./sql/createdata.sql;show warnings;commit;";
	mysql -h $(MYSQL_ENDPOINT) -u root -pPassw0rd -t -e "source ./sql/verification.sql;show warnings;commit;";
