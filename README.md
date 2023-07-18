# Utilisation

`docker-compose up -d` pour lancer les containers définis dans `docker-compose.yml`. 

Un des conteneurs est défini avec un `Dockerfile` qui built une image python3.9 et instale les librairies contenues dans `requirements.txt`.


Les containers python, mysql et phpmyadmin doivent être lancé et être actifs. On peut le vérifier avec `docker ps`.


Dans VS Code on peut ensuite F1 + "attach to a running container" pour développer dans le container.


Le code est ensuite push sur github depuis le terminal du container.