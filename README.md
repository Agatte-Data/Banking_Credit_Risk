# Tableau de Bord Bancaire - Suivi de l'Octroi et du Risque de Crédit

## 📌 Contexte du Projet
Ce projet consiste à concevoir un tableau de bord analytique sous **Power BI** pour une banque commerciale au Cameroun. L'objectif est de piloter le volume d'octroi de crédits tout en maîtrisant le risque de portefeuille (créances douteuses / NPL, PAR30, PAR90).

## 🛠️ Architecture du Projet
* `data/` : Jeu de données brutes comprenant 7 tables (Dimensions & Faits).
* `reports/` : Rapport Power BI (.pbix).
* `dax/` : Scripts des mesures DAX créées.
* `docs/` : Documentation technique, cahier des charges et capture des en-têtes de pages.

## 📊 Modèle de Données & KPIs
* **Modèle** : Schéma en étoile intégrant deux tables de faits (`Fait_Demande_Credit` et `Fait_Performance_Pret`).
* **KPIs principaux** :
  * Encours Total & Taux de NPL (%)
  * Portfolio at Risk (PAR30+ / PAR90+)
  * Taux d'approbation des demandes
  * Coût du risque & Provisions Totales

## 🚀 Outils Utilisés
* **Power Query** : Nettoyage, harmonisation et transformation des données.
* **Power BI / DAX** : Modélisation en étoile et calcul des indicateurs métiers.
* **Git / GitHub** : Versioning et documentation.