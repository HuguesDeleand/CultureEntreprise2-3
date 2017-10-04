# Exercice 2.3 du TP

### 1- Cloner le projet dans le dossier personnel
```bash
$ git clone https://github.com/HuguesDeleand/CultureEntreprise2-3
```

### 2- Se rendre au bon emplacement pour lancer docker 
```bash
$ cd CultureEntreprise2-3/hugues-deleand-2-3/wordpress
$ docker-compose up
```

### 3- Accéder à WordPress
Taper la commande `docker ps`, repérer l'image `wordpress:latest` et copier le `CONTAINER ID` correspondant. Lancer `docker inspect CONTAINER ID`. Dans la rubrique "Networks", le champ "IPAddress" indique l'IP permettant d'accéder à l'interface de WordPress.

Version de docker utilisée (sous Linux Mint 17.3) : `Docker version 17.06.2-ce, build cec0b72`

Version de docker-compose utilisée (sous Linux Mint 17.3) : `docker-compose version 1.16.1, build 6d1ac21`

