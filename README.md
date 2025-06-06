# Projet-Python
Analyse de donneés sur l'immobilier en France

# Analyse de l'Évolution des Transactions Immobilières en France (2018–2022)
## Objectif

Ce projet vise à **analyser l’évolution du marché immobilier français** entre 2018 et 2022, avec une attention particulière portée aux **ventes de maisons et d'appartements**. Nous étudions l’impact du **COVID-19** sur les préférences des acheteurs à travers l'analyse des bases de données foncières ouvertes.

---
## Environement et dépendances

- Python 3
- Jupyter Notebook / VS Code
- Bibliothèques :
  - `pandas`, `numpy` : traitement de données
  - `matplotlib`, `seaborn`, `plotly` : visualisation
  - `geopandas`, `folium`, `calmap`, `squarify` : cartes et graphiques avancés

---
---

## 🔍 Démarche

1. **Importation et nettoyage des données**
   - Suppression des lignes/colonnes vides
   - Formatage des champs (`date`, `valeurs`, `surfaces`)
   - Filtrage des biens d'intérêt : *Maisons* et *Appartements*

2. **Exploration du marché immobilier**
   - Analyse des types de mutations par année
   - Comparaison des surfaces moyennes acquises

3. **Analyse géographique**
   - Calcul du volume de ventes par département
   - Cartes des **variations de ventes** entre 2018 et 2022
     - Une pour les **maisons**
     - Une pour les **appartements**

---

## 🧪 Résultats

- **Tendance générale** : après la crise du COVID-19, les Français semblent avoir **délaissé les appartements** au profit des **maisons**, traduisant une volonté d’avoir plus d’espace.
- Les cartes produites montrent :
  - Une **augmentation** des ventes de maisons dans une grande majorité des départements.
  - Une **baisse généralisée** des ventes d’appartements sur la même période.

---

## 🚧 Difficultés rencontrées

- Limitations de **Google Colab** (temps d’exécution, visualisation) → migration vers **Visual Studio Code**
- Gestion de fichiers volumineux et nettoyage complexe de données non homogènes

---
