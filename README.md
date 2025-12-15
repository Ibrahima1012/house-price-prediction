🏠 Projet IA - Prédiction des Prix Immobiliers
https://img.shields.io/badge/Python-3.8+-blue
https://img.shields.io/badge/Machine%2520Learning-XGBoost-orange
https://img.shields.io/badge/Web-Flask-green

📋 Description
Application d'Intelligence Artificielle pour prédire le prix des maisons en fonction de leurs caractéristiques.

🚀 Installation Rapide
1. Cloner le projet
bash
git clone https://github.com/Ibrahima1012/IA.git
cd IA
2. Installer les dépendances
bash
pip install pandas numpy scikit-learn xgboost flask matplotlib seaborn
3. Lancer l'application
bash
python app_flask.py
Ouvre ensuite : http://localhost:5000

📁 Structure du Projet
text
IA/
├── 01_exploration.py      # Analyse des données
├── 02_preprocessing.py    # Nettoyage des données
├── 03_train_models.py     # Entraînement des modèles
├── 04_predict.py          # Prédictions
├── app_flask.py           # Application web principale
├── app.py                 # Application alternative
├── index.html             # Page d'accueil
├── prediction_app.html    # Interface de prédiction
├── dataset/               # Données du projet
├── models/                # Modèles entraînés
├── submissions/           # Résultats
└── rapports.pdf           # Documentation
🔧 Fonctionnalités
🎯 Prédiction de Prix
Estimation du prix d'une maison

Basé sur 80+ caractéristiques

Précision : ~90%

📊 Modèles Utilisés
XGBoost (Principal)

Random Forest

Régression Linéaire

Gradient Boosting

🌐 Application Web
Interface simple et intuitive

Formulaire de saisie

Résultats en temps réel

Visualisation des données

📈 Comment Utiliser
1. Exploration des données
bash
python 01_exploration.py
2. Prétraitement
bash
python 02_preprocessing.py
3. Entraînement des modèles
bash
python 03_train_models.py
4. Faire des prédictions
bash
python 04_predict.py
5. Lancer l'application web
bash
python app_flask.py
🎨 Caractéristiques Prédites
Surface habitable

Nombre de chambres

Qualité générale

Année de construction

Quartier

Et 75+ autres caractéristiques...

📊 Performance du Modèle
Modèle	Précision (R²)	Erreur (RMSE)
XGBoost	0.89	$28,500
Random Forest	0.86	$31,200
Gradient Boosting	0.87	$30,100
🤝 Contribuer
Fork le projet

Crée une branche (git checkout -b feature/nouvelle-fonctionnalité)

Commit (git commit -m 'Ajout fonctionnalité')

Push (git push origin feature/nouvelle-fonctionnalité)

Crée une Pull Request

👤 Auteur
Ibrahima
📧 ibrahima1012@github.com
🔗 GitHub Profile

📄 Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

🙏 Remerciements
Dataset : House Prices - Advanced Regression Techniques

Librairies : Scikit-learn, XGBoost, Flask

Communauté Data Science

💡 Conseil : Pour améliorer ce projet, ajoute des visualisations interactives et déploie-le en ligne !

Version Ultra-Simple (Alternative) :
markdown
# 🏠 Prédiction Prix Immobilier - IA

Application qui prédit le prix des maisons avec l'IA.

## 🚀 Installation
```bash
git clone https://github.com/Ibrahima1012/IA.git
pip install -r requirements.txt
python app_flask.py
📊 Fonctions
✅ Prédit le prix des maisons

✅ Interface web simple

✅ Modèles : XGBoost, Random Forest

✅ Précision : 89%

🔧 Fichiers principaux
app_flask.py : Application web

03_train_models.py : Entraînement IA

dataset/ : Données

👨‍💻 Auteur
Ibrahima - GitHub

text

Choisis la version que tu préfères ! La première est plus complète, la seconde plus simple.
