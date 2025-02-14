
# Dossier Images et Utilisation de Docker

Ce dossier contient plusieurs images liées à des jeux vidéo, notamment l'univers de Mario.  
Nous allons également voir comment utiliser Docker pour exécuter le jeu Super Mario dans un conteneur.


```docker
docker search pengbai/supermario
```

### Pengbai Mario
![Pengbai Mario](images/pengbaimario.png)

```docker
docker pull pengbai/docker-supermario
```
```docker
docker run -d --name supermario -p 8600:8080 pengbai/docker-supermario
```
```docker
docker run -d --name supermario2 -p 8700:8080 pengbai/docker-supermario
```
### Docker Super Mario
![Docker Super Mario](images/dockersupermario.png)

### Infinite Mario
![Infinite Mario](images/infinitemario.png)

### Mario Game
![Mario Game](images/mariogame.png)

### Nouveau Jeu
![Nouveau Jeu](images/newgame.png)

### Niveau 1
![Niveau 1](images/niveau1.png)

### Play Game
![Play Game](images/playgame.png)


## Différentes utilisations de Docker (Terminal/Desktop)

Pour chaque cas, nous allons voir comment résoudre le problème en utilisant le terminal et Docker Desktop.

### Arrêter un conteneur :

- **Avec le terminal** :  
  ```docker
  docker stop <nom_du_conteneur>

### Avec Docker Desktop :
Allez dans le menu "Containers" et, dans la section "Actions", cliquez sur l'icône de la corbeille pour supprimer le conteneur.

### Supprimer une image :
- **Avec le terminal** :
```docker
docker rmi <nom_de_l_image>
```

- **Avec Docker Desktop** :
Allez dans le menu "Images" et, dans la section "Actions", cliquez sur l'icône de la corbeille pour supprimer l’image.

