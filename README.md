---

# 🧠 MLP pour la prédiction du diabète

## 📌 Description
Ce projet implémente un **Perceptron Multicouche (MLP)** afin de prédire la présence de diabète à partir de données médicales.  
Le dataset utilisé est généralement le **Pima Indians Diabetes Dataset**, disponible dans `sklearn.datasets` ou sur Kaggle.

## 🎯 Objectifs
- Construire un modèle de classification supervisée.
- Évaluer les performances du MLP sur des données médicales.
- Comparer les résultats avec d’autres modèles de référence.

## 📂 Structure du projet
```
├── data/                # Données brutes ou prétraitées
├── notebooks/           # Notebooks Jupyter pour exploration
├── src/                 # Code source du modèle
│   ├── preprocessing.py # Prétraitement des données
│   ├── model.py         # Définition du MLP
│   └── train.py         # Script d'entraînement
├── results/             # Graphiques et métriques
└── README.md            # Documentation du projet
```

## ⚙️ Installation
1. Cloner le dépôt :
   ```bash
   git clone https://github.com/ton-compte/mlp-diabetes.git
   cd mlp-diabetes
   ```
2. Créer un environnement virtuel et installer les dépendances :
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   pip install -r requirements.txt
   ```

## 🚀 Utilisation
- Entraîner le modèle :
  ```bash
  python src/train.py
  ```
- Évaluer le modèle :
  ```bash
  python src/evaluate.py
  ```

## 📊 Métriques
Les performances sont évaluées avec :
- **Accuracy**
- **Précision**
- **Recall**
- **F1-score**
- **Courbe ROC / AUC**

## 🔮 Améliorations possibles
- Optimisation des hyperparamètres (GridSearch, RandomSearch).
- Ajout de régularisation (Dropout, L2).
- Comparaison avec d’autres architectures (CNN, RNN).
- Déploiement via une API Flask ou FastAPI.

## 👥 Contributeurs
- Auteur : [LOKOSSOU Dossou Kajarnak]
- Contributions bienvenues via **Pull Request**
- Licence MIT
- **contact** : +2290143667604
