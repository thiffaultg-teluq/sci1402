# Projet en science des données | SCI 1402
Dans le cadre du cours SCI 1402, soit le cours synthèse du certificat en science des données (4865).
Il est demandé aux étudiants d'appliquer les notions et méthodes acquises durant cette session par l'entremise 
d'un projet final. Ce projet final devait traiter des données massives.


Il était vivement conseillé d'utiliser le site Kaggle, afin d'un trouver un projet opportun. J'ai 
opté pour cette solution et choisi le projet [UCI Heart Disease Data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data).


## Contexte 
La tâche principale de ce projet est d’identifier les personnes à risque de développer des maladies du coeur : donc il est possible de parler d’un type de problème médical. 
Sans oublier la tâche expérimentale de diagnostiquer et de découvrir d’autres informations qui pourraient aider à mieux comprendre le problème.


## Enjeu
L’enjeu du projet est d’identifier des tendances et des patterns permettant aux médecins de pouvoir déceler plus rapidement chez leurs patients à risque ce type de problème.


## Hypothèse
L'hypothèse formulée est que plus une personne est âgée et que celle-ci a un haut taux de cholestérol, plus elle a de risques de développer des maladies cardiaques.


## Description du sommaire de la méthodologie
Lors de ce travail, PySpark et Panda via Google Colab ont été sollicités pour :
### Transformation des données :
- traitement des données manquantes; 
- traitement des données aberrantes;
- conversions des catégories en valeurs numériques.
### Modélisation :
La création d'un modèle d'apprentissage machine en régression logistique : 
- Création du modèle à partir des données traitées et filtrées
- Évaluation du modèle à partir de la métrique "précision" et de la variation croisée.


## Bonne lecture!
Je vous invite donc à consulter l'ensemble des travaux pratiques et le [Google Colab](https://colab.research.google.com/drive/1AT9H6Qu6CJifgjlFKNZH_HZl3e-bbb33)git