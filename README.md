# proxysql-docker

docker run -p 16032:6032 -p 16033:6033 -p 16070:6070 -d -v /path/to/proxysql.cnf:/etc/proxysql.cnf proxysql/proxysql

mysql -h127.0.0.1 -P16032 -uradmin -pradmin --prompt "ProxySQL Admin>"


