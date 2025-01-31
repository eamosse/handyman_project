# Projet final
Dans ce projet,  vous allez compléter l'application commencée en cours en y ajoutant des fonctionnalités de persistance dans des divers types de bases de données telles que : 
- Room : Base de données local
- API : Serveur Node JS
- Firebase

## Concepts et notions envisagés
- Room
- Retrofit
- Coroutines
- Préférences
- Menu

## Etape 1 : Synchroniser le projet précédent 
- Modifier le remote du TP précédent pour le pointer vers ce repository

## Etape 2: Mise en place de la base de données 
Dans cette section, vous allez ajouter les composants nécessaires permettant de gérer les utilisateurs dans une base de données SQLite. 
- Ajouter les composants nécessaires (Entity, DAO, Database) pour gérer les utilisateurs dans une base de données SQLite, en utilisant la librairie Room
- Ajouter une nouvelle implémentation du service afin de gérer la nouvelle source de données (i.e. base de données Room)
- Adapter le repository pour qu'il puisse s'instancier avec l'un ou l'autre des services (memory ou base de données)
- Ajouter un mécanisme permettant de remplir la base de données avec des données de tests

## Etape 3: Gestion des préférences
- Modifier la toolbar de l'application pour y ajouter un menu permettant de basculer sur le mode memory ou base de données
- Utiliser les Préférences pour sauvegarder le choix de l'utilisateur (memory ou database). Quand l'utilisateur choisit un mode dans le menu (memory ou database), sauvegarder son choix dans les préférences afin qu'au redémarrage de l'application son choix soit sauvegardé.

## Etape 4: Mise en place de la synchronisation avec l'API Rest
Pour cela, vous devez utiliser une API (Node JS) mise à votre disposition. Cette API contient les actions CRUD sur les utilisateurs. Vous devrez le modifier pour ajouter les actions supplémentaires comme l'ajout en favoris etc. 
Lien vers le projet Node [https://github.com/eamosse/neighbors_api]
Pour commencer : 
- Forker le repository git pour en créer une copie pour votre groupe.
- Modifier le README du projet de l'application Android en y ajoutant le lien vers votre repository de l'API

## Etape 5: Synchroniser votre application mobile avec l'API
A ce stade, votre application dispose de 3 sources de données : mémoire, locale et en ligne. Modifier la toolbar pour ajouter l'option Online.

## Etape 6 : Fonctionnalité supplémentaire (1 au choix) 
1. Permettre aux utilisateurs de prendre une photo en utilisant la caméra et synchroniser la photo avec le serveur
2. Permettre d'enregistrer l'adresse des utilisateurs au moment de la création. Pour cela, vous pouvez faire du reverse geocoding sur la postion de l'utilisateur ou utiliser Google Places API pour chercher une adresse.

# Etape 7: Utiliser Firebase (1 au choix) 
4. Ajouter une 4e source, en synchronisant vos données avec une base de données Firebase
5. Mettre en place une authentification en utilisant Firebase
6. Développer une fonctionnalité de chat en utilisant Firebase

# Contraintes :
- Repartir des sources du projet précédent
- Utiliser les coroutines
- Garder les mêmes groupes
- Utiliser l'injection de dépendances





