# PFE – Détection de maladies cardiaques par IA

Ce projet s'inscrit dans le cadre du Projet de Fin d'Études du Master 2 Informatique (UVSQ).

## Objectif

Développer et évaluer des modèles de machine learning pour prédire la présence d’une maladie cardiaque à partir du dataset UCI Heart Disease.

## Structure

- `data/` – Contient les données (non versionnées si sensibles)
- `notebooks/` – Notebooks Jupyter (EDA, modèles, expériences)
- `src/` – Scripts Python (prétraitement, modèles, utils)
- `reports/` – Figures, rapport, slides
- `requirements.txt` – Librairies nécessaires

## Plan qualité (version initiale)

- **Reproductibilité**
  - Environnement virtuel `.venv`
  - Dépendances listées dans `requirements.txt`
  - Seeds fixes dans tous les modèles
- **Organisation**
  - Code Python dans `src/`
  - Notebooks numérotés : `01-EDA.ipynb`, `02-Modeles.ipynb`
- **Données**
  - Pas de données sensibles dans Git
  - Fiche data-card pour décrire le dataset
- **Validation**
  - Split train/test stratifié
  - Validation croisée 5-fold
  - Métriques : F1, Recall, ROC-AUC, PR-AUC

# yityrtfyurfyryir
