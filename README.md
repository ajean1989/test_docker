# Utilisation

docker-compose up -d pour lancer les containers définie dans docker-compose.yml. 

Un des conteneurs est définit avec un Dockerfile qui built une image python et install les librairies contenues dans requirements.txt.


Les containers python, mysql et phpmyadmin doivent être lancé. On peut le vérifier avec docker ps.


Dans VS Code on peut ensuite F1 + "attach to a running container" pour développer dans le container.


Le code est ensuite push sur github depuis le terminal du container. S