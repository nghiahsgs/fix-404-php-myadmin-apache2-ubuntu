# fix-404-php-myadmin-apache2-ubuntu
fix 404 php myadmin apache2 ubuntu

```
sudo ln -s /etc/phpmyadmin/apache.conf /etc/apache2/conf-available/phpmyadmin.conf
sudo a2enconf phpmyadmin.conf
sudo systemctl restart apache2
```


```
sudo apt install libapache2-mod-php8.0
```
