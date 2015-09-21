# Nginx config for CakePHP application 
Nginx config file for CakePHP application running with PHP-FPM

## You should put the application.conf in Nginx sites config path
``
cp application.nginx /etc/nginx/sites-available/application.conf
ln -s /etc/nginx/sites-available/application.conf /etc/nginx/sites-enabled/application.conf
``
