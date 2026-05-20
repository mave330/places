# 🗺️ Mes Favoris Google Maps - Page Web Interactive

Bienvenue ! Cette page web affiche tous tes favoris Google Maps de manière moderne et facilement explorable.

## 📊 Statistiques

- **2183 lieux** enregistrés
- **50+ pays** représentés  
- **12+ types** de lieux (restaurants, cafés, hôtels, musées, etc.)
- Classés par **pays et ville**
- Liens directs vers **Google Maps**

## 🎨 Caractéristiques

✨ **Design sobre et moderne** - Inspiré par Notion  
🔍 **Filtres intelligents** - Par pays, type de lieu, ou recherche libre  
📱 **Responsive** - Fonctionne sur mobile et desktop  
⚡ **Léger et rapide** - Pas de dépendances externales sauf React  
🌍 **Classification automatique** - Détection du type de lieu depuis le nom  

## 🚀 Déploiement rapide

### Option 1: GitHub Pages (RECOMMANDÉ - Gratuit et simple)

1. Créé un compte GitHub (si tu n'en as pas)
2. Va sur https://github.com/new et crée un nouveau repo appelé `mon-nom.github.io`
3. Clone le repo: `git clone https://github.com/mon-nom/mon-nom.github.io.git`
4. Copie le fichier `index.html` dans le dossier cloné
5. Commit et push:
   ```bash
   git add index.html
   git commit -m "Ajout de mes favoris Google Maps"
   git push
   ```
6. Accède à: `https://mon-nom.github.io`

### Option 2: Netlify (Gratuit)

1. Va sur https://netlify.com
2. Connecte-toi avec GitHub
3. Drag and drop le fichier `index.html`
4. Tu recevras une URL publique automatiquement!

### Option 3: Vercel (Gratuit)

1. Va sur https://vercel.com
2. Crée un projet
3. Upload `index.html`
4. Accède via l'URL fournie

### Option 4: Locale (Pour explorer avant de publier)

Ouvre simplement `index.html` dans ton navigateur préféré!

## 📁 Fichiers inclus

- **index.html** - Page complète et autonome (données intégrées)
- **favorites.html** - Version avec chargement externe (utile pour mettre à jour les données)
- **places_data.json** - Données JSON traitées et classifiées

## 🔄 Mettre à jour les données

Si tu exportes de nouveaux favoris Google Maps:

1. Exporte-les depuis Google Maps (format GeoJSON ou JSON)
2. Traite-les avec le script Python (si tu as besoin d'aide)
3. Remplace les données dans le HTML

## 🎯 Utilisation

1. **Chercher**: Tape un nom, une adresse ou une ville dans la barre de recherche
2. **Filtrer par pays**: Clique sur les boutons de pays
3. **Filtrer par type**: Sélectionne un type de lieu (Restaurant, Café, etc.)
4. **Ouvrir dans Maps**: Clique sur "Voir sur Google Maps" pour ouvrir le lieu

## 💡 Astuces

- Les filtres se combinent (pays + type)
- La recherche fonctionne sur le nom, l'adresse ET la ville
- Les cartes s'animent au chargement pour un effet plus agréable
- La page est entièrement en français

## 🛠️ Personnalisation

Tu peux facilement modifier:
- **Couleurs**: Cherche `:root` dans le CSS et modifie les variables
- **Police**: Change `font-family` dans les styles
- **Layout**: Modifie `grid-template-columns` pour la grille

## 📞 Support

Si tu as besoin d'aide:
- Vérifie que le fichier `index.html` est bien à la racine
- Assure-toi que les données JSON sont au bon format
- Teste dans un navigateur moderne (Chrome, Firefox, Safari, Edge)

## 📄 Licence

Ces données te sont personnelles. Partage cette page comme tu le souhaites!

---

**Créée avec ❤️** - Profite de tes explorations! 🌍
