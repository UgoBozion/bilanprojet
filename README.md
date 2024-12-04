**# Installation de Docker et lancement de WordPress avec Docker Compose

## Étapes d'installation de Docker
1. **Télécharger et exécuter le script d'installation**  
   Pour installer Docker, lancez le script `install_docker.sh` avec la commande suivante :  
   `./install_docker.sh`

2. **Redémarrer la machine (si possible)**  
   Une fois l'installation terminée, il est recommandé de redémarrer votre machine pour garantir que Docker fonctionne correctement.

## Lancer WordPress avec Docker Compose
1. **Accéder au répertoire de WordPress**  
   Rendez-vous dans le répertoire où se trouve votre projet WordPress. Exécutez la commande suivante pour y accéder :  
   `cd /bilanprojet/wordpress`

2. **Lancer WordPress avec Docker Compose**  
   Une fois dans le répertoire, utilisez la commande suivante pour démarrer WordPress avec Docker Compose en mode détaché :  
   `docker compose up -d`  
   Cette commande va télécharger les images nécessaires et lancer les containers pour WordPress et sa base de données.

## Vérification du fonctionnement de WordPress
1. **Accéder à WordPress via le navigateur**  
   Ouvrez votre navigateur et entrez l'URL suivante pour vérifier que WordPress fonctionne correctement :  
   `http://Ipdelamachine:8000`  
   Remplacez `Ipdelamachine` par l'adresse IP de votre machine.


Pour installer Zabbix la démarche est la même, il faudra se rendre dans le repertoire zabbix et executer le fichier docker compose avec la commande docker compose up -d. 
Pour accèder a l'interface de zabbix il faudra cette fois taper l'ip de la machine avec 8080 a la fin . **# Installation de Docker et lancement de WordPress avec Docker Compose

## Étapes d'installation de Docker
1. **Télécharger et exécuter le script d'installation**  
   Pour installer Docker, lancez le script `install_docker.sh` avec la commande suivante :  
   `./install_docker.sh`

2. **Redémarrer la machine (si possible)**  
   Une fois l'installation terminée, il est recommandé de redémarrer votre machine pour garantir que Docker fonctionne correctement.

## Lancer WordPress avec Docker Compose
1. **Accéder au répertoire de WordPress**  
   Rendez-vous dans le répertoire où se trouve votre projet WordPress. Exécutez la commande suivante pour y accéder :  
   `cd /bilanprojet/wordpress`

2. **Lancer WordPress avec Docker Compose**  
   Une fois dans le répertoire, utilisez la commande suivante pour démarrer WordPress avec Docker Compose en mode détaché :  
   `docker compose up -d`  
   Cette commande va télécharger les images nécessaires et lancer les containers pour WordPress et sa base de données.

## Vérification du fonctionnement de WordPress
1. **Accéder à WordPress via le navigateur**  
   Ouvrez votre navigateur et entrez l'URL suivante pour vérifier que WordPress fonctionne correctement :  
   `http://Ipdelamachine:8000`  
   Remplacez `Ipdelamachine` par l'adresse IP de votre machine.

## Installation de Zabbix avec Docker Compose

1. **Accéder au répertoire de Zabbix**  
   Rendez-vous dans le répertoire où se trouve votre projet Zabbix. Exécutez la commande suivante pour y accéder :  
   `cd /bilanprojet/zabbix`

2. **Lancer Zabbix avec Docker Compose**  
   Utilisez la commande suivante pour démarrer Zabbix avec Docker Compose en mode détaché :  
   `docker compose up -d`  
   Cette commande va télécharger les images nécessaires et lancer les containers pour Zabbix.

## Vérification du fonctionnement de Zabbix
1. **Accéder à l'interface de Zabbix via le navigateur**  
   Ouvrez votre navigateur et entrez l'URL suivante pour vérifier que l'interface Zabbix fonctionne correctement :  
   `http://Ipdelamachine:8080`  
   Remplacez `Ipdelamachine` par l'adresse IP de votre machine.
