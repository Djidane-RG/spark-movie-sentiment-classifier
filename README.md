## Contexte :

Projet mené lors du certificat de spécialisation « Analyste de données massives » du Conservatoire National des Arts et Métiers (Cnam). 

## Objectif du projet et démarche :

L’objectif du projet est de prédire la note entre 1 à 10 des textes de revues de films issues de la base de données IMDB.
Je me suis donc orienté vers la construction d’un prédicteur obtenu par apprentissage supervisé. La démarche générale pour répondre au projet a été la suivante :
* Compréhension de la problématique que l’on cherche à résoudre ;
* Récupération des données textuelles et découverte de celles-ci ;
* Pré-traitement des données ;
* Représentations vectorielles des textes ;
* Création du plusieurs prédicteurs et choix du plus performant ;
* Conclusion et réflexions sur des pistes d’amélioration.

Le détail des différentes étapes est documenté dans le rapport au format pdf du projet qui est située à la racine de ce repository tandis que le code est disponible dans le notebook dédié.

## Aspects techniques : 

Le projet utilise Apache Spark pour le traitement distribué, et utilise des algorithmes de machine learning sur des données textuelles vectorisées.

![image](https://github.com/user-attachments/assets/d4cf7d50-2d47-447d-8d97-0f3bbad7749f)
