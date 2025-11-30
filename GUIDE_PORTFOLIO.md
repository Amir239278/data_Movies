# 📋 Guide : Ajouter Moviestar App à votre Portfolio GitHub

## Option 1 : Créer un nouveau dépôt GitHub (Recommandé)

### Étapes :

1. **Créer un nouveau dépôt sur GitHub**
   - Allez sur https://github.com/new
   - Nom du dépôt : `moviestar-app` ou `movie-recommendation-system`
   - Description : "Système de recommandation de films avec Machine Learning (KNN)"
   - Visibilité : Public (pour le portfolio)
   - Ne pas initialiser avec README (on a déjà un README)

2. **Préparer le projet localement**
   ```bash
   cd /c/Users/DELL/Desktop/PROJET_2/testP2/p2Movies
   
   # Changer le remote vers votre nouveau dépôt
   git remote remove origin
   git remote add origin https://github.com/Amir239278/moviestar-app.git
   
   # Vérifier
   git remote -v
   ```

3. **Ajouter et commiter les changements**
   ```bash
   git add README.md .gitignore
   git commit -m "✨ Amélioration du README pour portfolio
   
   - Ajout d'une section dédiée aux recruteurs
   - Badges et métriques du projet
   - Points forts mis en avant
   - Amélioration du .gitignore"
   ```

4. **Pousser vers GitHub**
   ```bash
   git push -u origin main
   ```

---

## Option 2 : Ajouter comme sous-projet dans wild-data-hub

Si vous préférez avoir tous vos projets dans un seul dépôt :

1. **Créer un dossier dans wild-data-hub**
   ```bash
   cd /c/Users/DELL/Desktop/P3_Data_Hub
   mkdir -p projects/moviestar-app
   ```

2. **Copier les fichiers essentiels** (sans .git, venv, etc.)
   ```bash
   # Copier uniquement les fichiers de code
   cp -r /c/Users/DELL/Desktop/PROJET_2/testP2/p2Movies/streamlit_app projects/moviestar-app/
   cp /c/Users/DELL/Desktop/PROJET_2/testP2/p2Movies/README.md projects/moviestar-app/
   cp /c/Users/DELL/Desktop/PROJET_2/testP2/p2Movies/requirements.txt projects/moviestar-app/
   ```

3. **Ajouter au dépôt**
   ```bash
   git add projects/moviestar-app/
   git commit -m "➕ Ajout du projet Moviestar App au portfolio"
   git push origin portfolio
   ```

---

## Option 3 : Fork du dépôt original (si vous voulez garder l'historique)

1. **Forker le dépôt original**
   - Allez sur https://github.com/jbhdev/data-films
   - Cliquez sur "Fork"
   - Choisissez votre compte

2. **Cloner votre fork**
   ```bash
   git clone https://github.com/Amir239278/data-films.git
   cd data-films
   ```

3. **Appliquer les améliorations**
   - Copier les fichiers README.md et .gitignore améliorés
   - Commit et push

---

## ✅ Recommandation

**Je recommande l'Option 1** car :
- ✅ Projet indépendant dans votre portfolio
- ✅ Facile à référencer dans votre CV
- ✅ Montre votre capacité à gérer des projets complets
- ✅ Plus professionnel pour les recruteurs

---

## 📝 Après avoir créé le dépôt

1. **Ajouter des topics sur GitHub** :
   - `data-science`
   - `machine-learning`
   - `recommender-system`
   - `streamlit`
   - `python`
   - `knn`
   - `movie-recommendation`

2. **Épingler le projet sur votre profil GitHub**

3. **Ajouter le lien dans votre CV** :
   ```
   Moviestar App - Système de Recommandation de Films
   GitHub: https://github.com/Amir239278/moviestar-app
   ```

---

## 🚀 Commandes rapides (Option 1)

```bash
cd /c/Users/DELL/Desktop/PROJET_2/testP2/p2Movies

# Changer le remote
git remote set-url origin https://github.com/Amir239278/moviestar-app.git

# Ou si le remote n'existe pas
git remote remove origin 2>/dev/null
git remote add origin https://github.com/Amir239278/moviestar-app.git

# Ajouter les changements
git add README.md .gitignore
git commit -m "✨ Amélioration pour portfolio"

# Pousser
git push -u origin main
```

