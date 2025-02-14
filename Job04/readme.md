# Jour 2 job04

Créer un fichier index.php avec ce code :

```docker
<?php 

phpinfo();

?>
```

Puis crée un fichier Dockerfile et utiliser ce code:

``` docker 
FROM php:apache

COPY index.php /var/www/html/

EXPOSE 80
```