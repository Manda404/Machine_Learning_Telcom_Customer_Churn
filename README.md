# Machine Learning Telcom Customer Churn

## 📌 Objectif du Projet

Ce projet vise à prédire le churn des clients d'un opérateur télécom, c'est-à-dire identifier les clients susceptibles de résilier leur abonnement. L'objectif est d'utiliser l'analyse des données et l'apprentissage automatique pour aider les entreprises à mettre en place des stratégies de fidélisation efficaces.

## 📊 Description du Dataset

Le dataset utilisé provient d'un échantillon de données clients fourni par IBM. Chaque ligne représente un client et chaque colonne décrit une caractéristique spécifique.

### 🔹 Informations Contenues :

- **Churn** : Indique si le client a résilié son abonnement (Oui/Non)
- **Services souscrits** : Téléphone, internet, sécurité en ligne, sauvegarde en ligne, support technique, streaming TV et films
- **Informations du compte** : Durée d’abonnement, type de contrat, méthode de paiement, facturation sans papier, montant des frais mensuels et totaux
- **Données démographiques** : Sexe, tranche d'âge, présence d’un conjoint ou d’enfants à charge

## 🚀 Inspiration

Ce projet permet d'explorer et d'apprendre les techniques de modélisation prédictive appliquées à la rétention client. Il s'agit d'un cas réel d'utilisation des modèles de Machine Learning pour optimiser les décisions business et améliorer l'expérience client.

## 🛠️ Technologies Utilisées

- **Python** 🐍
- **Pandas, NumPy** pour le traitement des données
- **Scikit-learn, XGBoost, CatBoost** pour la modélisation
- **Matplotlib, Seaborn** pour la visualisation
- **FastAPI** (optionnel) pour exposer un modèle via une API

## 📂 Structure du Projet

```
Machine_Learning_Telcom_Customer_Churn/
│── data/                # Contient le dataset brut et transformé
│── notebooks/           # Notebooks d'analyse exploratoire et de modélisation
│── src/                 # Code source pour le preprocessing et le modèle
│── tests/               # Tests unitaires pour valider les fonctions
│── requirements.txt     # Dépendances Python du projet
│── README.md            # Documentation du projet
│── .gitignore           # Fichiers à exclure du versionnement Git
```

## 📌 Comment Utiliser ce Projet ?

1. **Installer les dépendances** :
   ```sh
   pip install -r requirements.txt
   ```
2. **Exécuter l'analyse exploratoire et la modélisation** avec les notebooks.
3. **Tester les performances du modèle** sur l’ensemble de test.
4. **Déployer le modèle** avec FastAPI (optionnel).

## 📈 Résultats Attendus

- Une meilleure compréhension des facteurs influençant le churn
- Un modèle prédictif capable d'anticiper les départs clients avec une performance > 65%
- Des recommandations business pour réduire le churn

---

✨ **Auteur** : Rostand Surel
📅 **Date de création** : Mars 2025
=======