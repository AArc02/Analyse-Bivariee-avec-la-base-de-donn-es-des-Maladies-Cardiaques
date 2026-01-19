# Analyse des facteurs influençant le risque de maladies cardiaques



## Description du projet


Ce projet a pour objectif d’analyser les facteurs cliniques et démographiques influençant le risque de maladies cardiaques chez les patients.

L’étude repose sur le Heart Disease Dataset (Cleveland), un jeu de données largement utilisé en épidémiologie et en science des données médicales.

L’analyse se concentre sur :


  - Une analyse univariée afin de comprendre la distribution et le comportement de chaque variable prise individuellement.

  - Une analyse bivariée afin d’identifier les relations entre les variables explicatives et la variable cible indiquant la présence ou non d’une maladie cardiaque.


## Objectifs

- Explorer et comprendre les caractéristiques des patients

- Identifier les variables les plus associées au risque de maladie cardiaque

- Mettre en évidence des tendances cliniques pertinentes

- Préparer le terrain pour de futures analyses multivariées ou des modèles de prédiction

Jeu de données


## Source : Heart Disease Dataset (Cleveland)

Taille : 303 observations

### Variable cible :

target : présence (1) ou absence (0) de maladie cardiaque

Méthodologie

## Analyse univariée

- Statistiques descriptives (moyenne, médiane, écart-type)

- Étude des distributions

- Détection des valeurs aberrantes

- Visualisations : histogrammes, boxplots, bar charts


## Analyse bivariée

- Étude des relations entre les variables explicatives et target

- Comparaisons entre groupes (maladie vs non-maladie)

- Visualisations : boxplots, barplots, heatmaps

- Corrélations entre variables quantitatives


## Outils et technologies

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook
  

## Conclusion

Ce notebook a permis de couvrir les bases de l’analyse bivariée en s’appuyant sur la base de données des maladies cardiaques. 
Nous avons exploré de manière systématique les relations entre les variables quantitatives, qualitatives, 
ainsi que les interactions entre variables quantitatives et qualitatives,à l’aide d’outils graphiques et de mesures statistiques descriptives.

Les visualisations (boxplots, barplots, graphiques de dispersion, matrices de corrélation) ont facilité l’identification de tendances,
de différences significatives entre groupes et de relations potentielles avec la variable cible indiquant la présence 
ou l’absence d’une maladie cardiaque. Cette approche a permis de mieux comprendre l’influence de certains facteurs cliniques
et démographiques sur le risque cardiovasculaire.

Cette analyse bivariée constitue une étape essentielle avant la mise en œuvre de méthodes plus avancées, 
telles que l’analyse multivariée ou la modélisation prédictive. Elle fournit une base solide pour approfondir l’étude des facteurs de risque
et orienter le développement de modèles explicatifs ou de prédiction du risque de maladies cardiaque
