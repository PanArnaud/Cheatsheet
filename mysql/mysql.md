### Enable slow query log
Add following code to `etc/mysqld/mysqld.cnf` 
```slow_query_log = 1 
slow_query_log_file = /var/log/mysql/mysql-slow.log  
long_query_time = 2  
log-queries-not-using-indexes```
