# 🎯 Guide Rapide - Déploiement en 5 minutes

## Option A: GitHub Pages (La plus simple - RECOMMANDÉE)

### Étape 1: Créer un repo GitHub
1. Va sur https://github.com/new
2. **Nom du repo**: `mon-nom-utilisateur.github.io` (remplace `mon-nom-utilisateur`)
   - Par exemple: `alice.github.io` ou `bob123.github.io`
3. Clique sur "Create repository"

### Étape 2: Uploader le fichier
1. Dans ton nouveau repo, clique sur "Add file" → "Upload files"
2. Drag and drop le fichier `index.html`
3. Clique sur "Commit changes"

### Étape 3: Attendre ~2 minutes ⏳
1. Va dans l'onglet "Settings" du repo
2. Cherche "Pages" dans le menu de gauche
3. Attends le message ✅ "Your site is live"

### Étape 4: Accéder à ta page! 🎉
```
https://mon-nom-utilisateur.github.io
```

---

## Option B: Netlify (Encore plus simple!)

### Étape 1: Aller sur Netlify
1. Va sur https://app.netlify.com
2. Clique sur "Sign up" (tu peux te créer un compte gratuit)

### Étape 2: Upload le fichier
1. Clique sur "Drag to deploy"
2. Glisse-dépose `index.html` sur la zone
3. Attends ~30 secondes

### Étape 3: Accéder à ta page! 🎉
```
https://random-name.netlify.app
```

---

## Option C: Vercel

### Étape 1: Aller sur Vercel
1. Va sur https://vercel.com
2. Clique sur "Sign Up"

### Étape 2: Créer un projet
1. Clique sur "Create a new project"
2. Sélectionne "Import Git Repository" ou "Direct Upload"
3. Upload ou connecte ton repo

### Étape 3: Accéder à ta page! 🎉
L'URL est fournie automatiquement

---

## Option D: En local (Pour tester avant de publier)

1. Ouvre le dossier contenant `index.html`
2. Double-clique sur `index.html`
3. Ouvre-toi dans ton navigateur préféré!

---

## ❓ J'ai des problèmes

### La page affiche "Not Found" après le déploiement
- ⏳ Attends 2-3 minutes (GitHub Pages a besoin de temps)
- 📁 Vérifie que le fichier est nommé `index.html` (pas `Index.html`)

### Les données ne s'affichent pas
- 🔍 Ouvre la console (F12) et cherche les erreurs
- 💾 Vérifie que tu as utilisé le bon fichier `index.html` (celui avec données intégrées)

### Je veux personnaliser les couleurs
- 📝 Ouvre `index.html` avec un éditeur de texte
- 🎨 Cherche `:root { --` et modifie les couleurs (hex codes)
- 💾 Sauvegarde et redéploie

---

## 📸 À quoi ça ressemble?

La page est sobre et moderne, style Notion, avec:
- 📊 Statistiques en haut (total lieux, pays, types)
- 🔍 Barre de recherche
- 🏷️ Filtres par pays et type
- 🗺️ Cartes affichant tous tes lieux
- 🔗 Lien direct vers Google Maps pour chaque lieu

---

## 🎉 Et voilà!

Ta collection personnelle de favoris est maintenant en ligne!

Partage le lien avec qui tu veux, ou garde-le pour toi.

**Happy exploring! 🌍**
