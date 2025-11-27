# Détection de la Maladie de Parkinson par Analyse Vocale

![Parkinson's Disease](https://img.shields.io/badge/Parkinson's-Detection-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Python](https://img.shields.io/badge/Python-3.8%2B-brightgreen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Aperçu

Ce projet utilise des techniques d'apprentissage automatique pour détecter la maladie de Parkinson à partir de mesures vocales. Le modèle est basé sur un classificateur SVM (Support Vector Machine) et utilise des caractéristiques audio pour prédire la présence de la maladie avec une grande précision.

## Fonctionnalités

- Analyse des caractéristiques vocales pour détecter la maladie de Parkinson
- Nettoyage et prétraitement des données intégré
- Entraînement d'un modèle SVM optimisé
- Interface simple pour effectuer des prédictions
- Visualisation des données et des résultats

## Prérequis

- Python 3.8+
- Bibliothèques Python :
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib (pour la visualisation)
  - Seaborn (pour des visualisations avancées)

## Installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/parkinsons-detection.git
   cd parkinsons-detection
   ```

2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

## Utilisation

1. Exécutez le notebook Jupyter :
   ```bash
   jupyter notebook Parkinson's_Disease_Detection.ipynb
   ```

2. Suivez les étapes dans le notebook pour :
   - Charger et explorer les données
   - Prétraiter les données
   - Entraîner le modèle
   - Évaluer les performances
   - Faire des prédictions

## Résultats

Le modèle atteint une précision de plus de 90% sur l'ensemble de test, démontrant son efficacité dans la détection de la maladie de Parkinson à partir des caractéristiques vocales.

## Structure du Projet

```
parkinsons-detection/
├── data/
│   └── parkinsons.csv       # Jeu de données original
├── models/
│   └── model.pkl           # Modèle entraîné
├── notebooks/
│   └── Parkinson's_Disease_Detection.ipynb  # Notebook principal
├── README.md               # Ce fichier
└── requirements.txt        # Dépendances du projet
```

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

1. Forkez le projet
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Poussez vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.

## Contact

Lien du projet : https://github.com/makrame5/Parkinson-s_Disease_Detection

## Remerciements

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Parkinsons) pour le jeu de données
- La communauté open source pour les bibliothèques utilisées
- Tous les contributeurs qui ont aidé à améliorer ce projet
