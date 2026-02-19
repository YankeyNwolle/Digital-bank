# Digitalbank Landing Page

Une landing page moderne et responsive pour Digitalbank, une application bancaire numérique innovante. Ce projet démontre les principes de design responsive, d'accessibilité et de bonnes pratiques frontend.

> **Défi** : [Frontend Mentor - Digitalbank Landing Page](https://www.frontendmentor.io)

---

## 📸 Aperçu

La page présente une expérience utilisateur fluide et professionnelle avec :

- **En-tête sticky** avec navigation principale et CTA pour demander une invitation
- **Section héro** avec présentation du produit et mockup mobile
- **Section "Pourquoi Digitalbank"** avec 4 cartes de fonctionnalités clés
- **Section "Derniers articles"** pour le contenu éditorial
- **Footer** avec liens légaux et CTA secondaire

---

## ✨ Fonctionnalités implémentées

- ✅ Design responsive (Mobile: 375px → Desktop: 1440px)
- ✅ Navigation fluide et accessible
- ✅ Layout flexible avec CSS Flexbox
- ✅ Intégration de la typographie [Public Sans](https://fonts.google.com/specimen/Public+Sans) (poids: 300, 400, 700)
- ✅ Palette de couleurs cohérente (bleu marine, vert accent, gris neutre)
- ✅ Optimisation SEO basique
- ✅ Accessibilité (structure HTML sémantique)

---

## 🗂️ Structure du projet

```
digitalbank-landing-page-master/
├── index.html          # Structure HTML principale
├── css/
│   └── main.css       # Styles CSS (flexbox, responsive)
├── js/
│   └── app.js         # JavaScript (interactions, animations)
├── images/            # Ressources visuelles
│   ├── logo-dark.svg
│   ├── image-mockups.png
│   ├── icon-online.svg
│   ├── icon-budgeting.svg
│   ├── icon-onboarding.svg
│   ├── icon-api.svg
│   ├── image-currency.jpg
│   ├── image-restaurant.jpg
│   ├── image-plane.jpg
│   └── image-confetti.jpg
├── design/            # Fichiers de design (Figma - réf)
├── style-guide.md    # Guide de style et spécifications
├── README.md         # Ce fichier
└── .gitignore
```

---

## 🎨 Guide de style

### Couleurs

| Rôle | Couleur | Valeur |
|------|---------|--------|
| Primaire (Bleu) | Bleu 950 | `hsl(233, 26%, 24%)` |
| Accent (Vert) | Green 500 | `hsl(136, 64%, 51%)` |
| Accent (Cyan) | Cyan 400 | `hsl(192, 69%, 51%)` |
| Texte secondaire | Gray 600 | `hsl(233, 8%, 62%)` |
| Fond léger | Gray 100 | `hsl(220, 16%, 96%)` |
| Fond très léger | Gray 50 | `hsl(0, 0%, 98%)` |
| Blanc | White | `hsl(0, 100%, 100%)` |

### Typographie

- **Famille** : Public Sans (Google Fonts)
- **Poids** : 300 (light), 400 (regular), 700 (bold)
- **Taille de corps** : 18px

### Points de rupture

- **Mobile** : 375px
- **Desktop** : 1440px
- **Note** : Tester entre 320px et les grands écrans pour la responsivité complète

---

## 🚀 Installation et lancement

### Prérequis

- Navigateur moderne (Chrome, Firefox, Safari, Edge)
- Serveur local (optionnel, recommandé pour éviter les erreurs CORS)

### Installation

1. **Cloner le repository**
   ```bash
   git clone https://github.com/YankeyNwolle/Digital-bank
   cd digitalbank-landing-page-master
   ```

2. **Lancer un serveur local**

   Avec Python 3 :
   ```bash
   python -m http.server 5500
   ```

   Ou utiliser l'extension Live Server dans VS Code.

3. **Ouvrir dans le navigateur**
   ```
   http://localhost:5500
   ```

---

## 💻 Technologies utilisées

| Technologie | Utilisation |
|-------------|------------|
| **HTML5** | Structure sémantique, accessibilité |
| **CSS3** | Flexbox, responsive design, animations |
| **JavaScript (Vanilla)** | Interactivité, comportements dynamiques |
| **Google Fonts** | Typographie (Public Sans) |

---

## 🎯 Points clés du projet

### Architecture CSS
- Variables CSS pour une maintenabilité facile
- Approche mobile-first / responsive
- Structure claire et logique
- Support des états (hover, focus, active)

### Accessibilité
- Structure HTML sémantique (header, nav, section, footer)
- Attributs alt sur toutes les images
- Contraste suffisant pour la lisibilité
- Navigation au clavier possible

### Performance
- Assets optimisés
- Pas de dépendances lourdes (vanilla JS)
- CSS critique inline si nécessaire

---

## 📚 Fonctionnalités JavaScript (à mettre à jour)

Le fichier `js/app.js` gère :

- **Interactions des boutons CTA** : Demander une invitation
- **Navigation responsive** : Menu sur mobile (si hamburger implémenté)
- **Animations au scroll** : Révélation progressive des éléments
- **Gestion d'événements** : Comportements utilisateur enrichis

---

## ✅ Checklist de qualité

- [x] HTML valide et sémantique
- [x] Responsive sur la plage 320px - 1440px+
- [x] Respect du guide de style
- [x] Navigation accessible (clavier + lecteur d'écran)
- [x] Images d'accroche optimisées
- [x] Performance : Pas de dépendances inutiles
- [x] Code maintenable et commenté
- [ ] Tests cross-browser complets (à affiner)

---

## 🔍 Points d'amélioration possibles

- **Menu mobile hamburger** : Ajouter navigation responsive avec menu toggle
- **Formulaire de contact** : Section formulaire avec validation
- **Animations au scroll** : Révélations progressives avec Intersection Observer
- **Mode sombre** : Basculeur de thème avec localStorage
- **Optimisation Lighthouse** : Vérifier et améliorer les scores

---

## 📖 Ressources

- [MDN Web Docs](https://developer.mozilla.org/) - Documentation HTML, CSS, JavaScript
- [web.dev](https://web.dev) - Bonnes pratiques web modernes
- [A11y Project](https://www.a11yproject.com/) - Ressources accessibilité
- [Frontend Mentor](https://www.frontendmentor.io) - Challenges et communauté

---

## 👤 Auteur

Projet réalisé dans le cadre du défi Frontend Mentor « Digitalbank Landing Page ».

---

## 📄 Licence

Ce projet est fourni à titre éducatif. Les designs appartiennent à Frontend Mentor.

---

**Dernière mise à jour** : février 2026
