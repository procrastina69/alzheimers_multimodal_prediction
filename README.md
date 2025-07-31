# alzheimers_multimodal_prediction
A deep learning project combining brain MRI and clinical data to predict Alzheimer's disease status.

This project aims to build a deep learning pipeline that combines brain MRI images and structured clinical data to predict Alzheimer's disease severity.  
It leverages convolutional neural networks (CNN) and tabular data processing to produce a multimodal, interpretable AI model.

## Objective

Predict Alzheimer's disease status or severity using:
- Brain MRI scans (PNG)
- Clinical metadata (age, MMSE, CDR, etc.)

## Structure

| Dossier/Fichier        | Description                                             |
|------------------------|---------------------------------------------------------|
| `data/raw/`            | Données brutes téléchargées (IRM, CSV)                  |
| `data/processed/`      | Données nettoyées et prêtes à être utilisées            |
| `notebooks/`           | Jupyter notebooks d’exploration et de prototypage       |
| `src/data/`            | Scripts de chargement, nettoyage et transformation      |
| `src/models/`          | Scripts d’entraînement des modèles (image, tabulaire…)  |
| `src/visualization/`   | Scripts de visualisation (Grad-CAM, SHAP, graphiques)   |
| `models/`              | Poids des modèles sauvegardés (`.h5`, `.pt`)            |
| `app/`                 | Code de l’application Streamlit                         |
| `assets/`              | Images et captures pour la documentation                |
| `requirements.txt`     | Liste des dépendances Python                            |


## Data Source

- Dataset by @yiweilu2033 on Kaggle: [Well-documented Alzheimer's dataset](https://www.kaggle.com/datasets/yiweilu2033/well-documented-alzheimers-dataset)
- Based on OASIS-1 data

## Next steps

- [ ] Data ingestion and cleaning
- [ ] Exploratory analysis
- [ ] CNN model (images only)
- [ ] Tabular model
- [ ] Multimodal model (fusion)
- [ ] Interpretability (Grad-CAM, SHAP)
- [ ] Streamlit interface
- [ ] Final report + deployment
