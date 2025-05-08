# Détection de fraude - Projet Machine Learning (VESTA CORPORATION)

Ce projet vise à développer un modèle de machine learning pour détecter les fraudes dans les transactions.  


---

##  Arborescence du projet
01-ieee-fraud-detection/
├── .ipynb_checkpoints/
├── __pycache__/
├── 0_data/
├── 1_notebooks/
├── 3_ressources/
├── 4_models/
├── fraud_env_new/
├── PRESENTATION_FRAUD_DETECTION.pptx

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
