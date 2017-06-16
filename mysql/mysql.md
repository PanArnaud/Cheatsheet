### Enable slow query log
Add following code to `etc/mysqld/mysqld.cnf`  
```slow_query_log = 1 
slow_query_log_file = /var/log/mysql/mysql-slow.log  
long_query_time = 2  
log-queries-not-using-indexes```

### Load database from file
Create the database and execute the follwing command `mysql -u username -p database_name < file.sql`
