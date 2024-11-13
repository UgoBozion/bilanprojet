Installation Docker : 
Pour installer docker, il faudra récuperer le script install_docker.sh et lancer une installation avec la commande : 
./install_docker.sh 
Ensuite docker sera installé, il faudra possiblement redemarrer la machine. 
Par la suite il faudra créer un répertoire pour wordpress, puis y mettre le fichier docker compose du wordpress.
Ensuite, il suffira d'executer la commande docker-compose up -d. 
Pour vérifier le fonctionnement du wordpress il faudra rentrer http://Ipdelamachine:8000 dans le navigateur.
