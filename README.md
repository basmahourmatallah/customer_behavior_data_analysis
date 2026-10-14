# customer_behavior_data_analysis
Analyse du comportement d’achat des clients avec Python, PostgreSQL et Power BI.
Analyse du comportement d'achat des clients

# Projet data de bout en bout : nettoyage avec Python, stockage dans PostgreSQL, visualisation avec Power BI.

## Objectif

Analyser les habitudes d'achat de 3 900 clients : catégories les plus rentables, tranches d'âge qui dépensent le plus, part des clients abonnés et satisfaction moyenne.

## Données

customer_shopping_behavior.csv : 3 900 lignes, 18 colonnes (âge, genre, article, catégorie, montant, saison, note, abonnement, livraison, paiement, etc.).

## Outils

Python (pandas, SQLAlchemy, Jupyter) · PostgreSQL · Power BI · Git

Structure
├── data/raw/          # CSV d'origine
├── data/processed/    # données nettoyées
├── notebooks/         # exploration, nettoyage
├── reports/           # dashboard Power BI
└── requirements.txt

## Méthodologie

Exploration et nettoyage des données avec pandas
Chargement dans PostgreSQL (customer_behavior, table customer)
Requêtes SQL d'analyse
Dashboard Power BI avec filtres (abonnement, genre, catégorie, livraison)
