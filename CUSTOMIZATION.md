# 🎨 Guide de Personnalisation

## Modifier les Couleurs

Ouvre `index.html` avec un éditeur de texte et cherche cette section:

```css
:root {
    --bg-primary: #f9f9f7;        /* Arrière-plan principal (beige clair) */
    --bg-secondary: #ffffff;      /* Arrière-plan secondaire (blanc) */
    --text-primary: #1a1a1a;      /* Texte principal (noir) */
    --text-secondary: #6b6b6b;    /* Texte secondaire (gris) */
    --border-color: #e5e5e5;      /* Couleur des bordures (gris clair) */
    --accent: #4a4a4a;            /* Couleur d'accent (gris foncé) */
    --accent-hover: #2d2d2d;      /* Couleur au survol (gris très foncé) */
    --tag-bg: #f0ebe5;            /* Fond des tags (beige) */
    --tag-color: #5c5c5c;         /* Couleur du texte des tags */
}
```

## Exemples de Thèmes

### 🌙 Thème Sombre
```css
:root {
    --bg-primary: #1a1a1a;
    --bg-secondary: #2d2d2d;
    --text-primary: #ffffff;
    --text-secondary: #a0a0a0;
    --border-color: #444444;
    --accent: #64b5f6;
    --accent-hover: #42a5f5;
    --tag-bg: #3d3d3d;
    --tag-color: #e0e0e0;
}
```

### 🌸 Thème Rose
```css
:root {
    --bg-primary: #fff5f7;
    --bg-secondary: #ffffff;
    --text-primary: #4a0e4e;
    --text-secondary: #a85a8a;
    --border-color: #f0d5e0;
    --accent: #d946a6;
    --accent-hover: #c2185b;
    --tag-bg: #f8d4e6;
    --tag-color: #d946a6;
}
```

### 🌊 Thème Bleu
```css
:root {
    --bg-primary: #ecf0f7;
    --bg-secondary: #ffffff;
    --text-primary: #0c3c78;
    --text-secondary: #5a7e9d;
    --border-color: #d4dfe9;
    --accent: #1e88e5;
    --accent-hover: #1565c0;
    --tag-bg: #c5d9f2;
    --tag-color: #1e88e5;
}
```

### 🍃 Thème Vert (Nature)
```css
:root {
    --bg-primary: #f1f5f2;
    --bg-secondary: #ffffff;
    --text-primary: #1b4332;
    --text-secondary: #52796f;
    --border-color: #d4e3e0;
    --accent: #2d6a4f;
    --accent-hover: #1b4332;
    --tag-bg: #d8f3dc;
    --tag-color: #2d6a4f;
}
```

### 🌅 Thème Sunset
```css
:root {
    --bg-primary: #fff3e6;
    --bg-secondary: #ffffff;
    --text-primary: #6d4c41;
    --text-secondary: #a1887f;
    --border-color: #f0d9cd;
    --accent: #ff6f00;
    --accent-hover: #e65100;
    --tag-bg: #ffe0b2;
    --tag-color: #ff6f00;
}
```

## Codes Couleurs (Hex)

Voici des couleurs compatibles à mélanger:

### Neutres/Gris
- `#f9f9f7` - Beige très clair
- `#e5e5e5` - Gris clair
- `#999999` - Gris moyen
- `#4a4a4a` - Gris foncé
- `#2d2d2d` - Gris très foncé
- `#1a1a1a` - Quasi noir

### Bleus
- `#87ceeb` - Bleu ciel
- `#42a5f5` - Bleu vif
- `#1e88e5` - Bleu royal
- `#1565c0` - Bleu foncé

### Roses/Violets
- `#f8bbd0` - Rose clair
- `#f48fb1` - Rose vif
- `#d946a6` - Rose magenta
- `#8e24aa` - Violet

### Verts
- `#c8e6c9` - Vert clair
- `#81c784` - Vert moyen
- `#2d6a4f` - Vert foncé
- `#1b4332` - Vert très foncé

### Oranges/Rouges
- `#ffcc80` - Orange clair
- `#ff6f00` - Orange
- `#ff5252` - Rouge vif
- `#d32f2f` - Rouge foncé

## Changer la Police

Cherche cette ligne:
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', sans-serif;
```

Tu peux la remplacer par:

```css
/* Google Fonts (plus stylisé) */
font-family: 'Inter', sans-serif;
font-family: 'Poppins', sans-serif;
font-family: 'Montserrat', sans-serif;

/* Serif (plus classique) */
font-family: 'Merriweather', serif;
font-family: 'Georgia', serif;

/* Monospace (pour code) */
font-family: 'Courier New', monospace;
```

**Attention**: Si tu utilises une police Google Fonts, ajoute ceci au début du `<head>`:
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
```

## Changer le Titre

Cherche:
```html
<h1>Mes Favoris Google Maps</h1>
<p class="subtitle">Explorez tous mes lieux favoris enregistrés</p>
```

Et remplace par ce que tu veux!

## Changer la Taille de la Grille

Pour afficher plus ou moins de cartes par ligne, cherche:
```css
.places-grid {
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
}
```

Change `280px`:
- `280px` → Actuellement (3 cartes sur desktop)
- `350px` → Plus grand (2 cartes)
- `240px` → Plus petit (4 cartes)

## Exemple Complet: Thème Noir & Doré

```css
:root {
    --bg-primary: #0d0d0d;
    --bg-secondary: #1a1a1a;
    --text-primary: #ffffff;
    --text-secondary: #b0b0b0;
    --border-color: #333333;
    --accent: #d4af37;
    --accent-hover: #ffd700;
    --tag-bg: #2a2a2a;
    --tag-color: #d4af37;
}
```

## Besoin d'aide?

1. Sauvegarde une copie avant de modifier
2. Modifie une seule couleur à la fois
3. Sauvegarde et rafraîchis le navigateur (Ctrl+F5 ou Cmd+Shift+R)
4. Si c'est cassé, restaure la version précédente

Voilà! 🎨

Amusez-vous bien avec les couleurs!
