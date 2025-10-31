# Projet Gonorrhée - Économétrie des Big Data
**Étude prédictive d’un dépistage de la gonorrhée : préparation des données, analyse descriptive, modélisation (régression logistique, KNN, arbre de décision) et identification des groupes à risque.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)
![Word](https://img.shields.io/badge/Word-2B579A?style=for-the-badge\&logo=microsoft-word\&logoColor=white)

> Analyse réalisée en **Python** avec **Pandas** pour la préparation des données et **scikit-learn** pour la modélisation, **Word** pour la rédaction du rapport.

<br>

## 🛠️ Compétences mobilisées

* **Data cleaning & engineering** : gestion d’outliers, règles de valeurs manquantes, imputations et recodages binaires interprétables 
* **Réduction de redondance** : détection de variables corrélées (V de Cramer) et retrait de variables quasi dupliquées pour limiter la multicolinéarité. 
* **Analyse descriptive** : profilage des sous-groupes et mise en évidence de facteurs différenciants (sexe, orientation, activité, âge, statut marital)
* **Modélisation prédictive** : sélection de variables, régression logistique, KNN, arbre de décision avec recherche d’hyperparamètres. 
* **Évaluation & choix de modèle** : courbes ROC, AUC, précision/rappel/F1, test d’ajustement Hosmer-Lemeshow, arbitrage performance/interprétabilité. 
* **Interprétation** : lecture des **odds ratios**, caractérisation opérationnelle des **groupes à risque** et recommandations ciblées. 

<br>

## 🎯 Résultats clés

Les **profils à risque** ressortent d’une **régression logistique** entraînée sur des variables sociodémographiques et comportementales. Nous avons interprété les **odds ratios** et les **probabilités prédites** du modèle (seuil optimisé pour maximiser le F1-score) : le risque est **le plus élevé** chez les : 
> **hommes**, **< 30 ans**, **homosexuels** et à **forte activité** (nombre de partenaires élevé), tandis qu’il est **nettement plus faible** chez les profils **≥ 30 ans** à **faible activité**. 
