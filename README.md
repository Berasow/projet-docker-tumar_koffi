# Utilisation de l'application
## Créer les images
Dans un premier temps, il est nécessaire de créer les images, pour cela, placez vous dans le répertoire docker-project puis tapez cette commande : 
docker compose -f docker-compose.build.yml build


## Déployer les conteneurs
Ensuite, il faut déployer les conteneurs en utilisant les images qui viennent d'être créées. Cela va également créer les configurations, les volumes et les networks nécessaires au bon déploiement de l'application.\
Pour cela, tapez la commande suivante : 
docker compose up
