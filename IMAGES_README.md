# Guide de Remplacement des Images

## Images Actuellement Utilisées

Toutes les images du site utilisent actuellement Unsplash avec des images génériques. Pour mieux refléter le contexte du Burkina Faso et de l'Afrique de l'Ouest, il est recommandé de remplacer ces images par :

### 1. Images avec Personnes Africaines
- **Équipes professionnelles** : Utiliser des photos de votre équipe LBM ou des photos de professionnels africains
- **Formations** : Photos de sessions de formation avec participants africains
- **Conseil** : Photos d'équipes de conseil africaines

### 2. Images de Constructions Ouest-Africaines
- **BTP** : Photos de constructions typiques de l'Afrique de l'Ouest (Ouagadougou, Abidjan, etc.)
- **Architecture** : Bâtiments modernes ouest-africains
- **Chantiers** : Photos de vos propres projets de construction

### 3. Où Trouver des Images Adaptées

#### Banques d'Images Gratuites avec Contenu Africain :
- **Jolixi** : https://jolixi.com (banque d'images africaines)
- **Afripic** : https://afripic.com (photos africaines)
- **Afrikimages** : https://afrikimages.com (images d'Afrique centrale)
- **Pexels** : Rechercher "African professionals", "West Africa construction"
- **Pixabay** : Rechercher "African business", "Burkina Faso"

#### Images Locales (Recommandé) :
- Prendre vos propres photos de vos projets
- Utiliser des photos de votre équipe
- Photographier vos réalisations

### 4. Comment Remplacer les Images

#### Dans `index.html` :
- Ligne 54 : Hero image (construction)
- Lignes 111, 131, 151, 171, 191, 211 : Images des services
- Ligne 241 : Image de l'équipe (mission)

#### Dans `css/style.css` :
- Ligne 967 : Background page header
- Ligne 1073 : Background about image

### 5. Format Recommandé
- **Format** : JPG ou WebP
- **Taille** : 
  - Hero : 1920x1080px minimum
  - Services : 800x600px
  - Mission : 1200x800px
- **Poids** : Optimiser les images (max 500KB par image)

### 6. Exemple de Remplacement

```html
<!-- Avant -->
<img src="https://images.unsplash.com/photo-XXX" alt="Construction">

<!-- Après (image locale) -->
<img src="images/construction-ouagadougou.jpg" alt="Construction LBM à Ouagadougou">
```

### 7. Créer un Dossier Images

Créer un dossier `images/` à la racine du projet et y placer toutes vos images locales.

---

**Note** : Les images actuelles sont des placeholders. Pour un site professionnel adapté au contexte burkinabé, il est fortement recommandé d'utiliser des images locales ou provenant de banques d'images spécialisées dans le contenu africain.

