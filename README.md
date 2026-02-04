# 📉 Prédiction de churn client – Télécoms

## 🎯 Objectif
Prédire la résiliation (churn) des clients d’un opérateur télécom
afin d’identifier les profils à risque et améliorer la rétention.

## 🧠 Type de problème
- Machine Learning supervisé
- Classification binaire :
  - 0 : le client reste
  - 1 : le client résilie

## 📊 Données
- Dataset public (Kaggle – Telco Customer Churn)
- Données clients : contrat, facturation, services, ancienneté

## 🛠️ Stack prévue
- Python
- pandas, scikit-learn
- (à venir) FastAPI, Streamlit

## 🚀 Avancement
- [x] Définition du problème
- [ ] Analyse exploratoire (EDA)
- [ ] Entraînement du modèle
- [ ] API de prédiction
- [ ] Interface utilisateur

## 📌 Remarque
Ce projet est développé étape par étape dans un objectif de portfolio
Data Scientist, avec un focus sur la clarté, la reproductibilité et le raisonnement métier.

## 📂 Description du dataset

Le projet utilise un dataset public issu de Kaggle :
**Telco Customer Churn**.

### Contenu des données
Chaque ligne correspond à un client et contient notamment :
- informations démographiques (âge, seniorité)
- type de contrat et services souscrits
- facturation mensuelle et cumulée
- ancienneté du client
- variable cible : churn (Yes / No)

### Remarque
Le dataset brut n’est pas versionné dans ce repository.
Il doit être téléchargé séparément et placé dans le dossier :

