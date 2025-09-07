🔍 Phishing Detection / Détection de Phishing
🇬🇧 About the project

This project aims to build an intelligent phishing website detection system using machine learning techniques.
By analyzing features extracted from URLs and web pages, we trained a Random Forest classifier and deployed an interactive interface for easy use.

🚀 Features

● Data preprocessing and cleaning (duplicates, missing values, irrelevant columns).
● Exploratory Data Analysis (visualizations, correlations, class balance).
● Training and optimization of a Random Forest model.
● Model and scaler saving with joblib.
● Deployment of a web interface using Streamlit for real-time phishing detection.

🛠️ Technologies

● Python (pandas, numpy, scikit-learn, seaborn, matplotlib)
● Random Forest Classifier
● Streamlit for the user interface
● Joblib for model serialization

📊 Dataset

We used the dataset from Kaggle:
👉 Phishing Website Detector

It contains 11,055 records and 31 columns, including 30 features and 1 target variable (class: phishing or legitimate).

📂 Project Structure
detection-de-phishing/
├── models/                  # Saved models
├── phishing.csv             # Dataset (optional)
├── untitled8_(1)_(1).py     # Main script (training + Streamlit app)
├── requirements.txt         # Dependencies
└── README.md                # Documentation

▶️ Run the project
1. Clone the repository
git clone https://github.com/WafaeBouajaja/detection-de-phishing.git
cd detection-de-phishing

2. Install dependencies
pip install -r requirements.txt

3. Train the model (optional)
python untitled8_(1)_(1).py

4. Launch the Streamlit app
streamlit run untitled8_(1)_(1).py

📌 Results

● High accuracy (>95%) achieved with Random Forest.
● User-friendly interface to test a website and get a confidence score (legitimate or phishing).

🚀 Future Improvements

● Benchmarking with other algorithms (SVM, XGBoost, Deep Learning).
● REST API integration for external applications.
● Enhanced UI with more detailed visualizations.
● Real-time detection directly from user-provided URLs.
● Integration with cybersecurity tools to automatically block suspicious websites.

👩‍💻 Authors

Wafae Bouajaja

🔍 Détection de Phishing
🇫🇷 À propos du projet

Ce projet a pour objectif de concevoir un système intelligent de détection des sites de phishing en utilisant des techniques d’apprentissage automatique.
En analysant des caractéristiques extraites d’URLs et de pages web, nous avons entraîné un modèle de classification basé sur Random Forest, puis développé une interface interactive pour faciliter son utilisation.

🚀 Fonctionnalités

● Prétraitement et nettoyage des données (suppression des doublons, valeurs manquantes, colonnes inutiles).
● Analyse exploratoire des données (visualisation, corrélations, répartition des classes).
● Entraînement et optimisation d’un modèle Random Forest.
● Sauvegarde du modèle et du scaler avec joblib.
● Déploiement d’une interface web via Streamlit permettant de tester des sites en temps réel.

🛠️ Technologies utilisées

● Python (pandas, numpy, scikit-learn, seaborn, matplotlib)
● Random Forest Classifier
● Streamlit pour l’interface utilisateur
● Joblib pour la sérialisation du modèle

📊 Jeu de données

Le dataset utilisé provient de Kaggle :
👉 Phishing Website Detector

Il contient 11 055 enregistrements et 31 colonnes, dont 30 caractéristiques et 1 variable cible (class : phishing ou légitime).

📂 Structure du projet
detection-de-phishing/
├── models/                  # Modèles sauvegardés
├── phishing.csv             # Dataset (optionnel)
├── untitled8_(1)_(1).py     # Script principal (entraînement + app Streamlit)
├── requirements.txt         # Dépendances
└── README.md                # Documentation

▶️ Exécution
1. Cloner le dépôt
git clone https://github.com/WafaeBouajaja/detection-de-phishing.git
cd detection-de-phishing

2. Installer les dépendances
pip install -r requirements.txt

3. Entraîner le modèle (si besoin)
python untitled8_(1)_(1).py

4. Lancer l’application Streamlit
streamlit run untitled8_(1)_(1).py

📌 Résultats

● Précision élevée (>95%) grâce à l’algorithme Random Forest.
● Interface intuitive permettant aux utilisateurs de tester un site et d’obtenir un score de confiance (légitime ou phishing).

🚀 Améliorations futures

● Comparaison avec d’autres algorithmes (SVM, XGBoost, Deep Learning).
● Intégration d’une API REST pour une utilisation dans d’autres applications.
● Amélioration de l’interface utilisateur (visualisations plus détaillées).
● Détection en temps réel directement à partir d’URL saisies par l’utilisateur.
● Intégration avec un système de cybersécurité pour bloquer automatiquement les sites suspects.

👩‍💻 Auteurs

Wafae Bouajaja
