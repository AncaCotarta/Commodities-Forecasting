# Commodities Forecasting

Ce projet a pour objectif de prédire l'évolution des prix des commodités à partir de données historiques. En combinant l'analyse de données, la visualisation et des techniques de modélisation (régression, séries temporelles, etc.), ce projet offre une base pour explorer et anticiper les fluctuations du marché.

## Table des matières

- [Introduction](#introduction)
- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Contribution](#contribution)
- [Licence](#licence)
- [Contact](#contact)

## Introduction

Dans un contexte économique en constante évolution, la capacité à prévoir les tendances des prix des commodités est essentielle pour les décisions stratégiques et financières. Ce projet exploite des modèles statistiques et des algorithmes d'apprentissage automatique afin de fournir des prévisions robustes et fiables basées sur l'analyse de données historiques.

## Fonctionnalités

- **Prévision des prix** : Modélisation des séries temporelles et régression pour anticiper l'évolution des prix.
- **Analyse et visualisation des données** : Traitement et représentation graphique des données historiques.
- **Notebooks interactifs** : Exploration des données et ajustement des modèles via des notebooks Jupyter.

## Prérequis

- **Python** : Version 3.7 ou supérieure
- **Bibliothèques Python** :
  - `numpy`
  - `pandas`
  - `matplotlib` et/ou `seaborn`
  - `scikit-learn`
  - `statsmodels`

## Installation

1. **Cloner le dépôt** :
```bash
   git clone https://github.com/AncaCotarta/Commodities-Forecasting.git
```

2. **Créer et activer un environnement virtuel (optionnel mais recommandé)** :
```bash
  python3 -m venv env
    source env/bin/activate  # Sous Windows : env\Scripts\activate
```

3. **Installer les dépendances**  :
```bash
    pip install -r requirements.txt
```

## Utilisation

Pour exécuter le pipeline de prévision, vous pouvez utiliser le script principal :
```bash
python main.py
```
Vous trouverez également des notebooks Jupyter dans le dossier Jupyter Notebook qui permettent d’explorer les données et d’ajuster les modèles de manière interactive.

## Structure du projet

```bash
├── data/                  # Données brutes et données traitées
├── notebooks/             # Notebooks pour l'exploration des données et l'analyse
├── src/                   # Code source des scripts et modules
│   ├── preprocessing.py   # Traitement et nettoyage des données
│   ├── model.py           # Définition et entraînement des modèles
│   └── forecast.py        # Génération des prévisions
├── requirements.txt       # Liste des dépendances Python
├── main.py                # Script principal pour exécuter le pipeline
└── README.md              # Ce fichier
```

## Licence
Ce projet est distribué sous licence. Voir le fichier LICENSE pour plus de détails.

## Contact
Pour toute question ou suggestion, n'hésitez pas à contacter Anca Cotarta ou Ben Sassi Ilyes.
