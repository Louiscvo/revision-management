# 📚 Site de Révision Management & Communication

Site web responsive pour réviser le cours de Management et Communication, optimisé pour mobile.

## 🚀 Comment héberger sur GitHub Pages

### Étape 1 : Créer un repository GitHub

1. Allez sur [GitHub](https://github.com)
2. Cliquez sur le bouton `+` en haut à droite, puis `New repository`
3. Nommez votre repository (par exemple : `revision-management`)
4. Cochez `Public`
5. Cliquez sur `Create repository`

### Étape 2 : Uploader les fichiers

**Option A : Via l'interface web GitHub (plus facile)**

1. Dans votre nouveau repository, cliquez sur `Add file` > `Upload files`
2. Glissez-déposez le fichier `index.html`
3. Ajoutez un message de commit (par exemple : "Premier commit")
4. Cliquez sur `Commit changes`

**Option B : Via Git (en ligne de commande)**

```bash
cd /Users/louischavouet/Downloads/Photos

# Initialiser un repo git
git init

# Ajouter le fichier
git add index.html

# Faire un commit
git commit -m "Premier commit - site de révision"

# Ajouter le remote (remplacez USERNAME et REPO_NAME)
git remote add origin https://github.com/USERNAME/REPO_NAME.git

# Créer la branche main et push
git branch -M main
git push -u origin main
```

### Étape 3 : Activer GitHub Pages

1. Dans votre repository GitHub, allez dans `Settings` (Paramètres)
2. Dans le menu de gauche, cliquez sur `Pages`
3. Sous `Source`, sélectionnez `main` comme branche
4. Cliquez sur `Save`
5. Attendez quelques minutes

### Étape 4 : Accéder à votre site

Votre site sera accessible à l'adresse :
```
https://USERNAME.github.io/REPO_NAME/
```

Par exemple : `https://louischavouet.github.io/revision-management/`

## 📱 Utilisation sur mobile

1. Ouvrez l'URL de votre site sur votre téléphone
2. **Astuce iOS** : Ajoutez le site à l'écran d'accueil
   - Appuyez sur le bouton Partager (carré avec flèche)
   - Sélectionnez "Sur l'écran d'accueil"
   - Donnez-lui un nom court
   - Le site apparaîtra comme une app !

3. **Astuce Android** : Ajoutez le raccourci
   - Appuyez sur les 3 points en haut à droite
   - Sélectionnez "Ajouter à l'écran d'accueil"
   - Confirmez

## ✨ Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Navigation facile par sections
- ✅ Optimisé pour mobile
- ✅ Pas besoin de connexion une fois chargé (mise en cache)
- ✅ Contenu complet du cours
- ✅ Questions de révision
- ✅ Code couleur pour différencier les concepts

## 📂 Structure du contenu

1. **Accueil** : Vue d'ensemble
2. **Rôles Manager** : Les 10 rôles selon Mintzberg
3. **Modes Management** : Les 4 modes + délégation + évaluation
4. **Modèle DISC** : Les 4 profils + motivation
5. **Communication** : Processus + écoute active + techniques
6. **Obstacles** : Les 6 obstacles + solutions
7. **Quiz** : Questions de révision

## 🎨 Personnalisation

Si vous voulez modifier les couleurs, cherchez ces lignes dans `index.html` :

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Remplacez `#667eea` et `#764ba2` par vos couleurs préférées !

## 💡 Conseils d'utilisation

- Révisez une section par jour
- Utilisez le Quiz pour vous auto-tester
- Relisez les points clés avant l'examen
- Le site fonctionne hors-ligne une fois chargé

## 🔄 Mettre à jour le site

Pour modifier le contenu :
1. Éditez le fichier `index.html`
2. Uploadez-le à nouveau sur GitHub (écrasez l'ancien)
3. Les changements seront visibles en quelques minutes

---

**Bon courage pour vos révisions ! 🎯**
