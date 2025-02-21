# MySQL Server

MySQL Server berfungsi untuk server database

docker image :
```
mysql/mysql-server:latest
```

port : 
```
3306:3306
```

untuk port bisa di sesuaikan port yang kosong kemudian di forward ke port 3306

environtment :
```
MYSQL_ROOT_HOST=%
```
```
MYSQL_ROOT_PASSWORD=password
```
```
MYSQL_UNIX_PORT=/var/lib/mysql/mysql.sock
```
```
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

silahkan sesuaikan user dan password dengan kebutuhan masing-masing
