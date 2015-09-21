# Nginx config file for CakePHP application 
Nginx config file for CakePHP application running with PHP-FPM

You should copy the application.conf to "sites-available" path

``
 cp application.nginx /etc/nginx/sites-available/application.conf
``

And create a symbolic link to "sites-enabled"

``
 ln -s /etc/nginx/sites-available/application.conf /etc/nginx/sites-enabled/application.conf
``
