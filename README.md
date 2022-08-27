# dc_mysql-repl #

change in slave.sql ip adress user and password

## Restore dump from file  ##

$ docker exec -i some-mysql sh -c 'exec mysql -uroot -p"$MYSQL_ROOT_PASSWORD"' < /some/path/on/your/host/all-databases.sql
