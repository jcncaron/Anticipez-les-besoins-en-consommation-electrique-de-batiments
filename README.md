# Concevez-une-application-au-service-de-la-sante-publique

## Purposes of the project:

### finding innovative ideas for food-related applications from the Open Food Facts dataset
the dataset contains 4 different types of features:
1)	General information on the product sheet: name, date of modification, etc.
2)	A set of tags: product category, location, origin, etc.
3)	The ingredients making up the products and their possible additives.
4)	Nutritional information: amount in grams of a nutrient per 100 grams of product.


## Content of the repository : 
- Cleaning Jupyter Notebook : SantéPublique_NotebookNettoyage.ipynb\
        -> Cleaning and selecting convenient features for the app idea
- Exploratory Jupyter Notebook : SantéPublique_NotebookExplorationScoring.ipynb\
        -> Exploratory Data Analysis and Scoring for the application
- Slides of the presentation



# Anticipez-les-besoins-en-consommation-electrique-de-batiments
Projet 4 OpenClassRooms

Vous travaillez pour la ville de Seattle. Pour atteindre son objectif de ville neutre en émissions de carbone en 2050, votre équipe s’intéresse de près aux émissions des bâtiments non destinés à l’habitation.

Les données de consommation sont à télécharger à cette adresse : https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv

Problématique de la ville de Seattle :
Des relevés minutieux ont été effectués par vos agents en 2015 et en 2016. Cependant, ces relevés sont coûteux à obtenir, et à partir de ceux déjà réalisés, vous voulez tenter de prédire les émissions de CO2 et la consommation totale d’énergie de bâtiments pour lesquels elles n’ont pas encore été mesurées.

Votre prédiction se basera sur les données déclaratives du permis d'exploitation commerciale (taille et usage des bâtiments, mention de travaux récents, date de construction..)

Vous cherchez également à évaluer l’intérêt de l’"ENERGY STAR Score" pour la prédiction d’émissions, qui est fastidieux à calculer avec l’approche utilisée actuellement par votre équipe.

Votre mission :

Vous sortez tout juste d’une réunion de brief avec votre équipe. Voici un récapitulatif de votre mission :
- Réaliser une courte analyse exploratoire.
- Tester différents modèles de prédiction afin de répondre au mieux à la problématique.
- Avant de quitter la salle de brief, Douglas, le project lead, vous donne quelques pistes, et erreurs à éviter :

L’objectif est de te passer des relevés de consommation annuels (attention à la fuite de données), mais rien ne t'interdit d’en déduire des variables plus simples (nature et proportions des sources d’énergie utilisées). 

Fais bien attention au traitement des différentes variables, à la fois pour trouver de nouvelles informations (peut-on déduire des choses intéressantes d’une simple adresse ?) et optimiser les performances en appliquant des transformations simples aux variables (normalisation, passage au log, etc.).

Mets en place une évaluation rigoureuse des performances de la régression, et optimise les hyperparamètres et le choix d’algorithme de ML à l’aide d’une validation croisée.
