# conversion_rate_Classification

Ce projet consiste en la prediction d'une classe sous représentée (3% du dataset).

Nous essayerons plusieurs modèles de classification avec ou sans optimisation de parametrage issus de la librairie sklearn:
  -régression logistique
  -decision tree
  -random forest
  -SVM
  -gradient boosting decision tree
  
Nous utiliserons également des méthodes de redistribution des échantillons de la librairie imblearn:
  -SMOTE
  -SMOTEEN
  -SMOTETOMEK
  -TOMEKLINKS
  
  et un modèle:
  -BalancedRandomForestClassifier
  
 Ce projet fait l'objet d'un compétition Kaggle qui utilise comme métrique le F1 score (l'accuracy étant inapproprié ici).
 Les différentes méthodes utilisées ne permettent pas d'améliorer le F1 score significativement par rapport à une simple régression logistique, 
 mais ils permettent en revanche de modifier la précision sur les faux positifs et les faux négatifs ce qui en définitif pourrait être plus pertinent compte tenu des objectifs du projets  ( campagne d'amélioration des inscriptions à un site web).
