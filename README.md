# 🚀 Analyse Prédictive de la Rentabilité Retail

Ce projet présente une étude complète du jeu de données *Superstore*, allant du nettoyage des données brutes à la modélisation prédictive avec `Scikit-Learn`. L'objectif est d'aider la direction à optimiser ses marges en identifiant les facteurs clés de rentabilité.

---

## 📊 Résumé du Projet
* **Dataset :** 9 994 transactions, 21 variables.
* **Problématique :** Pourquoi la croissance des ventes ne se traduit-elle pas par une croissance proportionnelle des profits ?
* **Modèle ML :** `RandomForestClassifier` (précision : 94 %).

---

## 🛠 Workflow Technique
1. **Data Cleaning :** Traitement des types (`datetime`) et vérification de l'intégrité (0 valeur manquante détectée).
2. **Exploration (EDA) :** Visualisation de la saisonnalité et identification des *outliers* via des analyses statistiques.
3. **Analyse Stratégique :** Corrélation croisée entre les Ventes et les Bénéfices.
4. **Machine Learning :** Classification des transactions rentables vs non-rentables.

---

## 💡 Insights Clés
* **Le levier du "Discount" :** L'analyse d'importance des variables montre que la remise accordée est le facteur numéro 1 impactant la rentabilité, bien plus que le volume vendu.
* **Problématique des marges :** Les périodes de pics de ventes correspondent souvent à une érosion du profit, suggérant une politique de remises trop agressive à revoir.

---

## 📈 Résultats du Modèle
Notre modèle *Random Forest* permet de prédire la rentabilité d'une vente avec une précision de **94 %**, offrant un outil robuste pour anticiper les résultats des futures campagnes commerciales.
