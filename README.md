# Détection de fraude - Projet Machine Learning (VESTA CORPORATION)

Ce projet vise à développer un modèle de machine learning pour détecter les fraudes dans les transactions.  


---

##  Arborescence du projet


-----

## Arborescence du Projet : 01-ieee-fraud-detection

Cette structure organise le projet de détection de fraude IEEE en étapes logiques, de la donnée brute au modèle final et à la présentation.

```
.
├── 01-ieee-fraud-detection/
│   ├── 00_data/                                 # Données brutes et nettoyées (train/test).
│   ├── 01_notebooks/                            # Exploration (EDA), Pre-processing, Entraînement.
│   │   ├── 01_exploration_nettoyage.ipynb       # Nettoyage et Analyse Exploratoire des Données (EDA).
│   │   └── 02_entrainement_modele.ipynb         # Feature engineering et entraînement du modèle final.
│   ├── 02_ressources/                           # Images, schémas, notes de recherche, documentation externe.
│   ├── 03_models/                               # Fichiers de modèles sérialisés (ex: .pkl, .joblib, .h5).
│   │   └── model_final_lgbm.pkl                 # Exemple : Modèle final LightGBM sauvegardé.
│   ├── PRESENTATION_FRAUD_DETECTION.pptx      # Support de présentation du projet.
│   ├── README.md                                # Description du projet, installation et mode d'emploi.
│   ├── requirements.txt                         # Liste des dépendances Python requises pour l'environnement.
│   ├── fraud_env_new/                           # Environnement virtuel (si géré localement).
│   ├── .ipynb_checkpoints/                      # Dossier généré par Jupyter (à ignorer).
│   └── __pycache__/                             # Dossier généré par Python (à ignorer).
```

-----



## Instructions
Cloner le dépôt

Clonez ce dépôt sur votre machine :

bash
git clone <lien_du_repo>

## Ouvrir les notebooks

Lancez Jupyter Notebook ou JupyterLab, puis ouvrez les notebooks dans l'ordre suivant :

view : Pour explorer les datasets.

eda : Pour l'analyse exploratoire des données (EDA).

processing : Pour le traitement, l'encodage, la standardisation, etc.

1modeling.ipynb et 2modeling.ipynb : Pour l'entraînement et l'évaluation des modèles.

## Résultats

Le meilleur modèle obtenu est un Random Forest avec SMOTE (oversampling), qui a atteint :

AUC : 0.94

F2 score : 0.74


