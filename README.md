# Cinema-studio-analysis
# 🎬 Analyse Stratégique de la Performance des Films au Box-Office

## 📊 Objectif du Projet
Ce projet a pour but de fournir des insights stratégiques afin d'accompagner la création d’un nouveau studio de production de films. À partir d’analyses de données sur les genres, les performances au box-office et la qualité perçue des films, nous proposons des recommandations concrètes pour maximiser les chances de succès commercial et critique.

## 📂 Contenu du Répertoire
| Fichier / Dossier                      | Description |
| -------------------------------------- | ----------- |
| `Strategie_Studio_Boxoffice.ipynb`     | Notebook Jupyter contenant l'analyse complète (version interactive) |
| `Strategie_Studio_Boxoffice.pdf`       | Version PDF de la présentation du Notebook |
| `im.db`                                | Base de données SQLite contenant les informations de base sur les films |
| `movie_budget.csv`                     | Fichier CSV contenant les budgets de production et les recettes des films |
| `movie_gross.csv`                      | Fichier CSV des recettes domestiques et étrangères par studio |
| `ratings.tsv`                          | Fichier TSV contenant les évaluations des films (ratings) |
| `reviews.tsv`                          | Fichier TSV contenant les critiques des films (reviews) |

## 🛠 Méthodologie
1. **Exploration de la Base de Données** : Extraction des genres, ratings, et informations de production depuis la base SQLite.
2. **Intégration de Données Externes** : Fusion des fichiers CSV et TSV (budgets, recettes, ratings, reviews) avec la base.
3. **Analyses Réalisées** :
   - Genres les plus produits
   - Genres avec les notes moyennes les plus élevées
   - Test d’hypothèse : Comédies vs Films d’Action
   - Analyse des studios selon leur dépendance au marché international (ratio recettes étrangères/domestiques)
4. **Recommandations Stratégiques** basées sur les résultats.

## 📈 Technologies Utilisées
- **Python** (pandas, numpy, scipy, matplotlib)
- **SQLite3** pour la gestion de la base de données
- **Jupyter Notebook** pour les analyses et la présentation

## 📌 Auteurs
- **[Arven-Artchy Pierre-Louis]** – Data Analyst – [artchyvens2001@gmail.com]
