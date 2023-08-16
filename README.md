# ia-mongodb-cours-2021

## Installation

Bonjour, voici un cours de amaury , c'est cool !


Pour installer le serveur

docker compose up -d

## se connecter à la machine docker
docker exec -it mongo-db /bin/bash

## Se connecter au serveur mongodb avec mongosh
mongosh --username root --authenticationDatabase admin --password
(le mot de passe est test123*)

## Commandes utiles
- show dbs : lister les base de données
- use <db> : se connecter à une base de données
- show collections : lister les  collections

## Récupération de données

// use technocite
db = db.getSiblingDB ("technocite");



