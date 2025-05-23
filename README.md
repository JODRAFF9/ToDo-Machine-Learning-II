
<p align="center">
  <img src="docs/ansd.jpg" alt="Image 1" width="45%" />
  <img src="docs/ensae.png" alt="Image 2" width="45%" />
</p>

# TP Classification - Prédiction de classe de revenu

![Demo GIF](docs/vid.gif)


Ce projet est un travail pratique de classification supervisée visant à prédire si un individu gagne plus ou moins de **50 000$ par an**, à partir de variables socio-économiques. Il est basé sur un dataset classique issu du recensement américain.

## 📁 Contenu du projet

- `tp-classification-revenue.ipynb` : Notebook Jupyter contenant toutes les étapes du projet, de l'exploration des données à l'évaluation finale du modèle.

## 📊 Objectif

Utiliser des méthodes de machine learning supervisé pour construire un modèle de **classification binaire** permettant de prédire si le revenu d'une personne dépasse 50 000$.

## 🔧 Méthodologie

Le notebook passe  ces différentes étapes :

1. **Importation des bibliothèques**
2. **Chargement et compréhension des données**
3. **Nettoyage et traitement des données** :
   - Gestion des valeurs manquantes
   - Encodage des variables catégorielles
   - Standardisation des variables
4. **Exploration des données (EDA)** :
   - Visualisations des distributions
   - Analyse des corrélations
5. **Construction de modèles et Optimisation des paramètres et du seuil de discrimination** :
   - Dummy Classifier
   - Régression logistique
   - K plus proches voisins (KNN)
   - Random Forest
   - Gradient Boosting
6. **Évaluation des performances** :
   - Matrices de confusion
   - Accuracy, précision, rappel, F1-score
   - Courbes ROC
7. **Feature importance avec Shap**

## 📈 Résultats

Les performances des modèles sont comparées pour identifier celui offrant la meilleure capacité de prédiction.

## 🛠️ Prérequis

- Python ≥ 3.7
- Jupyter Notebook ou Jupyter Lab
- Bibliothèques :
  - `pandas`
  - `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`
  - `Shap`

## 🚀 Exécution

Pour exécuter le notebook :

```bash
jupyter notebook tp-classification-revenue.ipynb
```

## 📚 Données

Les données utilisées proviennent d'une version traitée du **Census Income Dataset** (Adult dataset) de l'UCI Machine Learning Repository.

## ✍️ Auteurs

- Réalisé par : Sié Rachid Traoré
- Sous la supervision de : Mme Mously Diaw
- Formation : ENSAE – TP de Machine Learning

---
---
---
<p align="center">
  <img src="docs/ansd.jpg" alt="Image 1" width="45%" />
  <img src="docs/ensae.png" alt="Image 2" width="45%" />
</p>