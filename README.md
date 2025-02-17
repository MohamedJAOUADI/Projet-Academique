# Projet_Académique


## Objectif
- Développer un système analytique pour centraliser, transformer et restituer les données de vente d’une entreprise.

## Réalisations
- **Pipelines ETL** : Conception des flux ETL pour automatiser le traitement des données.
- **Modélisation de données** :
  - Création d’un modèle en étoile avec une table de faits (ventes) et des dimensions (produits, clients, régions, temps).
  - Utilisation des SCD Type 1 et Type 2 pour gérer l’évolution des données dans les dimensions.
- **Transformation & Historisation** :
  - Implémentation des surrogate keys pour maintenir la cohérence entre la table des faits et les tables de dimensions. .
  - Intégration des calculs dérivés et des agrégats pour accélérer les analyses.
- **Analyses et Restitutions des données** :
  - Implémentation du modèle dans des outils de Data Visualisation comme Tableau.
  - Analyses, reporting, visualisation des données.

## Technologies
- **Base de données** : SQL Server
- **ETL** : SSIS (SQL Server Integration Services)
- **Visualisation** : Tableau Software

