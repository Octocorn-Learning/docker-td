# TD Docker

## Prérequis

- [Docker](https://docs.docker.com/get-docker/)

## Objectifs

- Créer un Dockerfile capable de servir une application basique

## Instructions

- Créer un fichier `Dockerfile` à la racine du projet
- Créer une image à partir de ce Dockerfile
- Lancer un conteneur à partir de cette image

## Etapes :

- Utiliser l'image de base `node:alpine`
- Définir le répertoire de travail dans le conteneur sur `/app/node`
- Copier les fichiers du projet dans le conteneur dans le dossier `/app/node`
- Importer les dépendances du projet
- Exposer le port 3000
- Lancer l'application avec la commande `npm start`
