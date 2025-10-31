# Analyse exploratoire du dataset AI4I 2020 - Maintenance prédictive

## Objectif du projet
Ce projet vise à explorer et nettoyer le jeu de données AI4I 2020 pour démontrer des compétences en data cleaning et analyse exploratoire (EDA).

## Description du dataset
Le dataset provient de l’UCI Machine Learning Repository : [AI4I 2020 Predictive Maintenance](https://doi.org/10.24432/C5HS5C)  
Licence : Creative Commons Attribution 4.0 International (CC BY 4.0)

Le dataset contient des mesures de processus industriel et des étiquettes de défaillance pour des machines simulées.

## Technologies utilisées
- Python 3.13.5
- Pandas
- NumPy
- Seaborn / Matplotlib
- Jupyter Notebook

## Étapes réalisées
1. Inspection initiale des données
2. Nettoyage des données (duplications, erreurs typographique, valeurs manquantes, valeurs aberrantes)
3. Analyse exploratoire (distribution, corrélations, boxplots, scatterplots, lineplots)
4. Feature engineering (création de colonnes dérivées pour l’analyse)

## Conclusions
- Certaines variables (ex. `Torque [Nm]`, `Rotational speed [rpm]`) sont fortement corrélées avec la défaillance machine.
- Les visualisations permettent de détecter les tendances et anomalies du processus.

## Instructions pour exécuter le notebook
1. Cloner le repo :
```bash
git clone https://github.com/anbialek/IndustrialMachineFailureDataAnalysis.git
```
2. Installer les dépendances :
```bash
pip install -r requirements.txt
```
3. Ouvrir le notebook :
```bash
jupyter notebook notebooks/02_data_cleaning_eda.ipynb
```