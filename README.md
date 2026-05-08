# TP N°1 : Classification de Clients avec Random Forest 🌌

[![Theme](https://img.shields.io/badge/Thème-Astronomic_Violet_Blue-8a2be2.svg)](#)
[![Algorithm](https://img.shields.io/badge/Algorithme-Random_Forest-00e5ff.svg)](#)

## 📌 Description du Projet

Ce projet a été réalisé dans le cadre du module d'Intelligence Artificielle / Analyse de Données. [cite_start]L'objectif est de répondre à une problématique d'entreprise souhaitant classer automatiquement ses clients pour adapter sa stratégie marketing[cite: 3]. 

[cite_start]Il s'agit d'un problème de classification supervisée résolu à l'aide de l'algorithme **Random Forest**[cite: 4]. Le projet est présenté sous la forme d'une page Web interactive unique (monolithique) au design thématique galaxie ("Astronomic Violet Blue").

### 👥 Équipe
* **Réalisé par :** Dahane Ahmed Lamine & Tabbi Meriem
* **Enseignante :** Mme. Fergani

---

## 📊 Jeu de Données (Dataset)

[cite_start]Le projet utilise le **Mall Customers Dataset**[cite: 5]. [cite_start]Il s'agit d'un jeu de données synthétique couramment utilisé pour l'apprentissage des techniques de segmentation de la clientèle[cite: 199].

* [cite_start]**Taille :** 200 enregistrements, 5 variables[cite: 202].
* [cite_start]**Attributs :** `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`[cite: 204].
* [cite_start]**Labellisation personnalisée :** Les données d'origine n'étant pas labellisées pour la classification supervisée [cite: 8][cite_start], nous avons créé nos propres étiquettes en segmentant les consommateurs en 3 classes selon leurs revenus (`Income`)[cite: 9].

---

## 🛠️ Fonctionnalités de l'Application Web

Le fichier HTML généré contient :
1. **Explications Théoriques :** Définition de l'algorithme Random Forest, de la technique du Bagging, et des métriques d'évaluation (Matrice de confusion, Précision, etc.).
2. **Code Source Python :** Le script complet de la solution (traitement des données, entraînement du modèle avec `scikit-learn`, et évaluation).
3. **Visualisations Interactives :** Graphiques générés avec Plotly.js pour explorer les résultats du modèle :
   * *Feature Importance* (Poids des variables).
   * *Matrice de Confusion* interactive.

---

## 🚀 Comment utiliser ce projet ?

Ce projet est "zéro configuration" (Serverless). Tout est contenu dans un seul fichier.

1. Clonez ce dépôt GitHub sur votre machine locale :
   ```bash
   git clone <votre-lien-github>
