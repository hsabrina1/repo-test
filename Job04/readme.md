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

Créer ton image:
 ``` docker
 docker build -t mon-apache-php .
 ```

 ``` docker
 docker run -d -p 8080:80 --name mon-container-apache mon-apache-php
 ```