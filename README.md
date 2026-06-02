# dashboard-bi-immobilier
projet-bi-analyse-immobiliere
# Real Estate BI Dashboard – Projet d’Analyse et de Business Intelligence Immobilière

## Présentation du projet

Ce projet consiste en la conception d’un dashboard de Business Intelligence dédié à l’analyse et au pilotage d’un parc immobilier à l’aide de Python, Pandas et Power BI.

L’objectif était de transformer des données immobilières brutes en indicateurs exploitables afin de produire des analyses métiers et des visualisations interactives adaptées à un contexte professionnel de reporting immobilier.

---

# Objectifs du projet

* Nettoyer et préparer un dataset immobilier complexe
* Réaliser une analyse exploratoire des données (EDA)
* Identifier les facteurs influençant les prix immobiliers
* Construire des dashboards interactifs sous Power BI
* Produire des insights métier pour l’aide à la décision

---

# Dataset utilisé

Dataset : Ames Housing Dataset

Le dataset contient :

* 2 930 logements
* 82 variables liées :

  * aux quartiers
  * aux types de logements
  * à la qualité des habitations
  * aux surfaces
  * aux garages
  * aux sous-sols
  * aux rénovations
  * aux prix de vente

---

# Technologies utilisées

## Traitement des données

* Python
* Pandas
* NumPy

## Visualisation de données

* Matplotlib
* Seaborn

## Business Intelligence

* Power BI

---

# Nettoyage et préparation des données

Plusieurs opérations de preprocessing ont été réalisées afin d’améliorer la qualité des données avant l’analyse.

## Gestion des valeurs manquantes

* Suppression des colonnes contenant trop de valeurs manquantes :

  * Pool QC
  * Misc Feature
  * Alley
  * Fence

* Remplacement des valeurs numériques manquantes par la médiane

* Remplacement des valeurs catégorielles manquantes selon une logique métier :

  * “No Garage”
  * “No Basement”

## Feature Engineering

Création de nouveaux indicateurs métier :

* Prix au m²
* Renommage et traduction des colonnes importantes pour faciliter l’analyse

---

# Analyse exploratoire des données (EDA)

Plusieurs analyses ont été réalisées afin de mieux comprendre le marché immobilier.

## Analyse des prix par quartier

Identification des quartiers les plus chers et des écarts de prix entre les différentes zones.

## Impact de la qualité des logements

Analyse de la relation entre la qualité des logements et les prix immobiliers.

Résultat :
Les logements de meilleure qualité présentent des prix significativement plus élevés.

## Surface habitable vs Prix

Étude de la corrélation entre la surface habitable et le prix de vente.

Résultat :
Une forte corrélation positive a été observée entre la surface et le prix des logements.

## Analyse des types de logements

Comparaison des prix moyens selon les catégories de logements :

* maisons individuelles
* duplex
* townhouses

---

# Dashboards Power BI

## Dashboard 1 – Analyse et Pilotage Immobilier

KPI principaux :

* Prix moyen des logements
* Surface habitable moyenne
* Prix moyen au m²
* Nombre total de logements

Visualisations interactives :

* Top quartiers les plus chers
* Évolution des prix selon les années de rénovation
* Impact de la qualité des logements sur les prix
* Prix moyens selon les types de logements

Filtres interactifs :

* Quartier
* Type de logement
* Qualité du logement<img width="509" height="288" alt="image" src="https://github.com/user-attachments/assets/e63d53a4-a878-4cd6-9664-0e7fa9c68a15" />


---

## Dashboard 2 – Insights & Recommandations

Analyses complémentaires :

* Impact de la capacité du garage sur le prix
* Répartition des logements par quartier
* Évolution des constructions immobilières
* Analyse Surface vs Prix via un scatter plot

Ce dashboard permet de :

* suivre les performances immobilières
* faciliter le reporting
* analyser les tendances du marché
* soutenir la prise de décision

---

# Principaux insights obtenus

* Certains quartiers présentent des prix immobiliers nettement supérieurs à la moyenne
* La qualité des logements influence fortement leur valorisation
* Les grandes surfaces sont généralement associées à des prix plus élevés
* Les logements avec de grands garages présentent des prix moyens supérieurs
* Les constructions récentes montrent une valorisation croissante

---

# Valeur métier du projet

Ce projet démontre :

* le nettoyage et la préparation de données
* la création de KPI métiers
* le développement de dashboards Power BI interactifs
* la production de reporting décisionnel
* l’analyse de données immobilières
* une approche orientée Business Intelligence

---

# Résultat final

Le projet aboutit à la création d’un dashboard BI professionnel simulant un environnement réel de reporting immobilier et d’aide à la décision pour des entreprises du secteur du logement et de la gestion immobilière.
