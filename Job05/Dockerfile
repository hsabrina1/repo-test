FROM php:7.4-apache

COPY index.php /var/www/html/
COPY result.json /var/www/html/
COPY save.php /var/www/html/

EXPOSE 8080

CMD ["apache2-foreground"]