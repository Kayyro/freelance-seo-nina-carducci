## 🚀 Résultats des Optimisations (Lighthouse)

| Axe | Score Initial | Score Final | État |
| :--- | :---: | :---: | :---: |
| **Performance** | 74 | **96** | ✅ |
| **Accessibilité** | 67 | **100** | ✅ |
| **Best Practices** | 100 | **100** | ✅ |
| **SEO** | 73 | **100** | ✅ |

---

## 🛠️ Liste complète des modifications

### 💻 Bugs JavaScript
- [x] **Filtre galerie** : Ajout de la classe `active` sur le filtre sélectionné pour un retour visuel utilisateur.
- [x] **Navigation modale** : Correction de la logique d'incrémentation (index `i-1` / `i+1`) pour la navigation *précédent/suivant* dans la lightbox.

### 🔍 SEO (Référencement Naturel)
- [x] **Sémantique** : Ajout de l'attribut `lang="fr"` et optimisation de la hiérarchie des titres (H1 à H3).
- [x] **Métadonnées** : Configuration des balises `title` et `description` uniques.
- [x] **Social Media** : Implémentation des protocoles **OpenGraph** (Facebook/LinkedIn) et **Twitter Cards**.
- [x] **SEO Local** : Mise en place des données structurées **Schema.org** (JSON-LD) pour le référencement de l'établissement local.

### ⚡ Performance
- [x] **Images Nouvelle Génération** : Conversion de tous les assets au format **WebP**.
- [x] **Responsive Images** : Redimensionnement des images à leur taille d'affichage réelle.
- [x] **Lazy Loading** : Ajout de l'attribut `loading="lazy"` sur les images hors écran pour économiser de la bande passante.
- [x] **Optimisation du rendu** : Ajout des attributs `width` et `height` pour éviter les sauts de mise en page (CLS) et utilisation de `defer` pour les scripts.

### ♿ Accessibilité
- [x] **Contrastes** : Correction des contrastes de couleurs sur les filtres et le carrousel (respect des normes **WCAG**).
- [x] **Sémantique HTML5** : Utilisation des balises structurelles (`<header>`, `<main>`, `<nav>`, `<section>`).
- [x] **Navigation assistée** : Ajout d'attributs `alt` descriptifs, de `aria-label` sur les liens sociaux et liaison correcte des `labels/inputs`.
- [x] **Validation** : Score de **0 erreur** sur l'outil de diagnostic **WAVE**.

---

## 📦 Technologies utilisées
* **HTML5 / CSS3** (Bootstrap 5)
* **JavaScript / jQuery**
* **SEO** : JSON-LD (Schema.org), OpenGraph
* **Outils d'audit** : Lighthouse, WAVE, Google Rich Snippet Test