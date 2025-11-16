### First Startup script to launch Apache2 Server
```
sudo su -
apt install apache2 -y
echo "Hello World $(hostname) IP Address:$(hostname -i)" > /var/www/html/index.html
service apache2 start
```
 