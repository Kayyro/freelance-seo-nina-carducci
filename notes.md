# 🛠️ Liste complète des modifications

## 💻 Bugs JavaScript
- [x] **Filtre galerie** : Ajout de la classe `active` sur le filtre sélectionné pour un retour visuel utilisateur.
- [x] **Navigation modale** : Correction de la logique d'incrémentation (index `i-1` / `i+1`) pour la navigation *précédent/suivant*.

## 🔍 SEO (Référencement Naturel)
- [x] Ajout de l'attribut `lang="fr"` sur la balise `<html>`.
- [x] Optimisation du `<head>` : déplacement de la balise `<meta charset>` en première position.
- [x] Ajout d'un `<title>` unique et pertinent.
- [x] Ajout d'une balise `<meta name="description">`.
- [x] Correction de la hiérarchie des titres :
  - h1 → Nina Carducci
    - h2 → A propos de moi
    - h2 → Portfolio
    - h2 → Mes services
      - h3 → Shooting photo
      - h3 → Retouches
      - h3 → Album photos
    - h2 → Une question ? Une demande de devis ?
- [ ] Mise en place des balises **OpenGraph** (pour le partage Facebook/LinkedIn).
- [ ] Configuration des **Twitter Cards**.
- [ ] Implémentation des données structurées **Schema.org** (SEO local).

## 🚀 Performance
- [x] **Format WebP** : Compression et conversion de toutes les images.
- [x] **Responsive Images** : Redimensionnement des assets à leur taille d'affichage réelle.
- [x] **Scripts** : Ajout de l'attribut `defer` sur toutes les balises `<script>`.
- [ ] Ajout de `loading="lazy"` sur les images hors écran.
- [ ] Ajout des attributs `width` et `height` sur les images.

## ♿ Accessibilité & Sémantique
- [x] Ajout d'attributs `alt` descriptifs sur toutes les images.
- [x] Liaison des `<label>` aux `<input>` via les attributs `for="id"`.
- [x] Ajout d'un `aria-label` sur le lien Instagram.
- [x] Restructuration sémantique : `<header>`, `<main>`, `<nav>`, `<section>`.
- [x] Landmark `<main>` ajouté.
- [ ] Correction des contrastes de couleurs (normes WCAG).

## 📊 Scores Lighthouse
| Axe | Départ | Actuel | Objectif |
|-----|--------|--------|----------|
| Performance | 74 | 96 | ≥ 90 ✅ |
| Accessibilité | 67 | 92 | ≥ 90 ✅ |
| Best Practices | 100 | 100 | ≥ 90 ✅ |
| SEO | 73 | 100 | ≥ 90 ✅ |