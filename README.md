
# 🔮 Time Series Forecasting : Énergie (Gaz & Électricité)

## 📌 Description

Ce projet a pour objectif d’analyser et de prédire la **consommation énergétique** d’une région sur plusieurs années. Il se concentre sur les usages suivants :

- ⚡ **Électricité**  
- 🔥 **Gaz**  
- 📊 **Consommation Totale** (Gaz + Électricité)

Grâce aux méthodes de **séries temporelles**, l’étude fournit une analyse poussée ainsi que des prévisions basées sur différents modèles classiques et de Deep Learning.

## 📂 Ce que contient le projet

- 📈 Analyse exploratoire et visualisation des données énergétiques  
- ⏳ Préparation et transformation des données temporelles  
- 🧠 Entraînement de plusieurs modèles prédictifs :
  - ARIMA / SARIMA  
  - GARCH  
  - ANN / RNN / LSTM / GRU avec TensorFlow  
- 🔍 Évaluation comparative des performances des modèles  
- 🧪 Génération de prévisions sur la consommation future d’énergie

## 🛠️ Technologies utilisées

- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- Statsmodels  
- TensorFlow / Keras

## 📊 À propos des données

Le jeu de données couvre la période de **2012 à 2024**, avec des relevés horaires comprenant :
- Date et heure  
- Consommation de gaz  
- Consommation d’électricité  
- Consommation totale  

## 📌 Résultats observés

L’analyse met en évidence des tendances claires à l’échelle horaire, hebdomadaire et saisonnière.  
Elle montre que :
- Les modèles de Deep Learning, comme le LSTM, sont performants pour les prévisions à long terme.  
- Les modèles statistiques tels que ARIMA et SARIMA sont plus adaptés aux prévisions à court terme.
