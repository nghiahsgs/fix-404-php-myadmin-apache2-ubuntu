# fix-404-php-myadmin-apache2-ubuntu
fix 404 php myadmin apache2 ubuntu

```
sudo ln -s /etc/phpmyadmin/apache.conf /etc/apache2/conf-available/phpmyadmin.conf
sudo a2enconf phpmyadmin.conf
sudo systemctl restart apache2
```
