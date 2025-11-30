# 🎬 Moviestar App - Système de Recommandation de Films

> Application web intelligente de recommandation de films utilisant le Machine Learning (KNN) pour suggérer des films personnalisés

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.45+-red.svg)](https://streamlit.io/)
[![Machine Learning](https://img.shields.io/badge/ML-KNN-FF6F00.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**🔗 Lien du projet :** [GitHub](https://github.com/Amir239278/data_Movies)

---

## 👔 Pour les Recruteurs

Ce projet démontre mes compétences en :
- **Machine Learning** : Implémentation d'un système de recommandation avec K-Nearest Neighbors (KNN)
- **Data Science** : Analyse et traitement de données de films (10K+ films)
- **Développement Web** : Application interactive avec Streamlit et interface moderne
- **Feature Engineering** : Préparation et transformation des données pour le ML
- **Optimisation** : Mise en cache, compression des données pour des performances optimales

**Technologies maîtrisées :** Python, Pandas, scikit-learn, KNN, Streamlit, Joblib, Data Processing

---

![Moviestar Logo](streamlit_app/assets/moviestar2.png)

Bienvenue dans **Moviestar App**, une application web de recommandation de films intelligente qui vous aide à découvrir des films adaptés à vos goûts.

## 🌟 Fonctionnalités principales

- 🎥 **Exploration de films** : Parcourez une vaste collection de films
- 🔍 **Recherche avancée** : Trouvez des films par titre, réalisateur ou acteur
- 🤖 **Recommandations personnalisées** : Découvrez des films similaires à ceux que vous aimez
- 💾 **Ma liste** : Enregistrez vos films préférés pour plus tard
- 📱 **Interface moderne** : Design réactif et convivial

## 🎯 Fonctionnalités techniques

- Système de recommandation basé sur KNN (K-Nearest Neighbors)
- Filtrage collaboratif pour des suggestions personnalisées
- Mise en cache intelligente pour des performances optimales
- Mise à jour en temps réel des recommandations

## 🛠️ Technologies utilisées

- **Frontend** : 
  - Streamlit pour l'interface utilisateur
  - HTML/CSS personnalisé
  - Animations Lottie pour une meilleure expérience utilisateur

- **Backend** : 
  - Python 3.9+
  - Pandas pour la manipulation des données
  - Scikit-learn pour les algorithmes de machine learning
  - Joblib pour la sérialisation des modèles

- **Optimisation** :
  - Données compressées pour des temps de chargement rapides
  - Mise en cache des résultats de recherche
  - Gestion efficace de la mémoire

## ⚙️ Installation locale

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/Amir239278/data_Movies.git
   cd data_Movies
   ```

2. **Créer un environnement virtuel** (recommandé) :
   ```bash
   python -m venv venv
   source venv/bin/activate  # Sur Windows: .\venv\Scripts\activate
   ```

3. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```

4. **Lancer l'application** :
   ```bash
   streamlit run streamlit_app/app.py
   ```

## 📊 Structure des données

L'application utilise des fichiers de données pré-traités pour des performances optimales :

- `processed_films_compressed.pkl.gz` : Données transformées pour KNN
- `nn_model_compressed.pkl.gz` : Modèle KNN entraîné
- `nn_distances_compressed.pkl.gz` : Distances et indices pré-calculés

## 📱 Fonctionnalités avancées

### Recherche intelligente
- Recherche par titre, réalisateur ou acteur
- Suggestions en temps réel
- Filtrage par genre et année

### Page de détail des films
- Affiche les informations complètes du film
- Recommandations de films similaires
- Accès rapide au réalisateur et aux acteurs

### Ma liste
- Ajoutez des films à votre liste personnelle
- Consultez vos films enregistrés à tout moment
- Interface intuitive pour gérer votre collection

## 🚀 Déploiement

L'application peut être déployée sur n'importe quelle plateforme supportant Streamlit, comme :
- Streamlit Cloud
- Heroku
- AWS/GCP/Azure
- Docker

## 📈 Résultats & Métriques

- **Base de données** : Plus de 10 000 films
- **Performance** : Temps de chargement moyen < 2 secondes
- **Algorithme** : K-Nearest Neighbors (KNN) pour recommandations
- **Précision** : Recommandations basées sur similarité de contenu et filtrage collaboratif

## 🎯 Points Forts du Projet

✅ **Production-Ready** : Application fonctionnelle et déployable  
✅ **ML-Powered** : Système de recommandation intelligent avec KNN  
✅ **User-Friendly** : Interface moderne et intuitive  
✅ **Optimisé** : Mise en cache et compression pour performances optimales  
✅ **Scalable** : Architecture modulaire et extensible

## 👤 Auteur

**Amir Meraka** - [@Amir239278](https://github.com/Amir239278)

💼 **Disponible pour des opportunités en Data Science / Machine Learning**

## 👥 Contributeurs

Un grand merci à tous les contributeurs qui ont participé à ce projet :

- [Sandrine banien](https://github.com/sandrineyb) - Développeur & Data analyst
- [Jean-Baptiste Hallassou](https://github.com/jbhdev) - Développeur & Data analyst
- [Anthony Desnous](https://github.com/anthodess) - Développeur & Data analyst
- [Amir Meraka](https://github.com/Amir239278) - Développeur & Data analyst

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus d'informations.

## 🙋‍♂️ Support

Pour toute question ou problème, veuillez ouvrir une issue sur le dépôt GitHub.

## 📊 Statistiques

- Plus de 10 000 films dans la base de données
- Interface optimisée pour tous les appareils
- Temps de chargement moyen inférieur à 2 secondes