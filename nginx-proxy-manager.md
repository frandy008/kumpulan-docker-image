# Nginx Proxy Manager

Tools ini digunakan untuk mempermudah melakukan reverse proxy karena sudah berbasis GUI

Untuk image nya :
```
jc21/nginx-proxy-manager:latest
```

Untuk port yang di gunakan :
```
80:80
443:443
81:81
```
Untuk port silahkan di sesuaikan.

Untuk volume nya bisa menggunakan bind : 
```
/srv/dockerdata/NGINXProxyManager/data:/data
/srv/dockerdata/NGINXProxyManager/letsencrypt:/etc/letsencrypt
```

Jika berhasil di install maka bisa di akses melalui :
```
http://ipaddress:81
```
