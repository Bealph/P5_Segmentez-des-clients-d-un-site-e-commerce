Projet "Anticipez les besoins en consommation de bâtiments"

Introduction :

Ce projet a été réalisé dans le cadre du parcours de formation en Data Science avec OpenClassrooms. Il s’inscrit dans un contexte où la ville de Seattle ambitionne de devenir neutre en émissions de carbone d’ici 2050. L’objectif est de prédire les émissions de CO2 et la consommation totale d’énergie des bâtiments non résidentiels à partir de leurs caractéristiques structurelles (taille, usage, date de construction, localisation, etc.), sans dépendre de relevés annuels coûteux. Les données utilisées proviennent de relevés effectués en 2016 par la ville de Seattle.

Objectifs du projet :

- Prédiction des émissions de CO2 : Estimer les émissions de CO2 des bâtiments à partir de leurs données structurelles.
- Prédiction de la consommation totale d’énergie : Prévoir la consommation énergétique en se basant sur les mêmes caractéristiques.
- Évaluation de l’ENERGY STAR Score : Intégrer ce score dans la modélisation et analyser son utilité pour améliorer les prédictions, tout en tenant compte de sa complexité de calcul actuelle.
  
Structure du repository :

Le repository contient les fichiers suivants :

- DIALLO_Alpha_1_notebook_exploratoire_032023.ipynb : Notebook Jupyter dédié à l’analyse exploratoire des données. Il inclut des visualisations, l’identification des variables pertinentes et la préparation des features.
- DIALLO_Alpha_2_notebook_prediction_032023.ipynb : Notebook Jupyter pour la prédiction des émissions de CO2, avec les tests de différents modèles de machine learning, l’optimisation des hyperparamètres et l’évaluation des performances.
- DIALLO_Alpha_3_notebook_prediction_032023.ipynb : Notebook Jupyter pour la prédiction de la consommation totale d’énergie, suivant une méthodologie similaire au notebook précédent.
- DIALLO_Alpha_4_presentation_032023.pptx : Support de présentation PowerPoint pour la soutenance, résumant les étapes clés et les résultats du projet.

Méthodologie :

- Analyse exploratoire : Identification des variables structurelles clés (taille, usage, localisation) et déduction d’informations supplémentaires (par exemple, à partir des adresses ou des sources d’énergie utilisées lors des relevés de référence).
- Modélisation : Tests de différents algorithmes de machine learning avec optimisation des hyperparamètres via validation croisée. Attention particulière portée à éviter les fuites de données (exclusion des relevés annuels futurs).
- Évaluation : Mesure des performances des modèles pour garantir des prédictions fiables et exploitables.
  
Livrables :

Ce projet comprend quatre livrables principaux :

- Notebook d’analyse exploratoire : Présente les observations initiales et la préparation des données.
- Notebook de prédiction des émissions de CO2 : Détaille les tests de modèles et sélectionne le meilleur pour cette tâche.
- Notebook de prédiction de la consommation d’énergie : Suit la même logique pour la consommation totale d’énergie.
- Support de présentation : Résume le projet pour la soutenance, avec les résultats clés et des recommandations stratégiques.
  
Ces livrables illustrent une approche complète, de l’analyse des données brutes à la production de prédictions utiles pour la gestion énergétique et environnementale.

Conclusion :

Ce projet démontre comment le machine learning peut anticiper les besoins en consommation des bâtiments, soutenant ainsi l’objectif de neutralité carbone de Seattle. Explorez les notebooks pour plonger dans la méthodologie ou consultez la présentation pour une vue d’ensemble.
