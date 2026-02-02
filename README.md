# IMMOLUXE.SN - Application Mobile PWA

Application mobile Progressive Web App (PWA) pour IMMOLUXE.SN - Agence Immobilière de Prestige

## 📱 Fonctionnalités

- ✅ **Application installable** sur iOS, Android et Desktop
- ✅ **Mode hors ligne** avec Service Worker
- ✅ **Interface responsive** optimisée pour mobile
- ✅ **Navigation fluide** avec menu drawer
- ✅ **Formulaires interactifs** pour les demandes clients
- ✅ **Sauvegarde locale** des données de formulaire
- ✅ **Design moderne** avec animations et effets visuels
- ✅ **Performance optimisée** avec mise en cache

## 🚀 Installation

### Installation sur Mobile (Android/iOS)

1. **Ouvrez l'application dans votre navigateur mobile**
   - Chrome (Android)
   - Safari (iOS)

2. **Android (Chrome):**
   - Cliquez sur le menu (⋮) en haut à droite
   - Sélectionnez "Ajouter à l'écran d'accueil" ou "Installer l'application"
   - Confirmez l'installation

3. **iOS (Safari):**
   - Appuyez sur le bouton de partage (📤)
   - Faites défiler et sélectionnez "Sur l'écran d'accueil"
   - Appuyez sur "Ajouter"

### Installation sur Desktop

1. **Chrome/Edge:**
   - Cliquez sur l'icône d'installation (➕) dans la barre d'adresse
   - Ou allez dans Menu > Installer IMMOLUXE

## 📦 Déploiement

### Option 1: Netlify (Recommandé)

1. Créez un compte sur [Netlify](https://www.netlify.com)
2. Glissez-déposez le dossier de l'application
3. Votre application sera en ligne en quelques secondes

### Option 2: Vercel

1. Installez Vercel CLI: `npm install -g vercel`
2. Dans le dossier de l'application: `vercel`
3. Suivez les instructions

### Option 3: GitHub Pages

1. Créez un dépôt GitHub
2. Uploadez les fichiers
3. Activez GitHub Pages dans les paramètres

## 🛠️ Structure du Projet

```
immoluxe-app/
├── index.html          # Page principale
├── app.js             # Logique de l'application
├── sw.js              # Service Worker pour mode hors ligne
├── manifest.json      # Configuration PWA
├── icons/             # Icônes de l'application
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md          # Ce fichier
```

## 🎨 Personnalisation

### Modifier les Couleurs

Dans `index.html`, recherchez les variables CSS:
- Couleur principale: `#ffd700` (or)
- Couleur de fond: `#1a1a2e` (bleu foncé)
- Couleur secondaire: `#16213e`

### Ajouter des Services

Dans `app.js`, modifiez le tableau `services`:
```javascript
const services = [
    {
        icon: '🏞️',
        title: 'Nom du service',
        description: 'Description du service'
    }
];
```

### Modifier les Informations de Contact

Éditez la section `#contact` dans `index.html`

## 📊 Fonctionnalités Techniques

### Service Worker
- Mise en cache des ressources statiques
- Fonctionnement hors ligne
- Stratégie "Cache First"

### Stockage Local
- Sauvegarde automatique des formulaires
- Conservation des soumissions hors ligne
- Synchronisation lors de la reconnexion

### Performance
- Chargement optimisé des ressources
- Images compressées
- Code minifié (recommandé en production)

## 🔒 Sécurité

- Formulaires protégés contre les injections
- Validation côté client
- HTTPS requis pour PWA (en production)

## 📱 Tests

### Tester en Local

1. Installez un serveur HTTP simple:
   ```bash
   npm install -g http-server
   ```

2. Lancez le serveur:
   ```bash
   http-server
   ```

3. Ouvrez http://localhost:8080

### Tester sur Mobile

1. Utilisez ngrok pour exposer votre serveur local:
   ```bash
   ngrok http 8080
   ```

2. Scannez le QR code ou utilisez l'URL fournie

## 🌐 Compatibilité

- ✅ Chrome (Android/Desktop)
- ✅ Safari (iOS/macOS)
- ✅ Edge (Desktop)
- ✅ Firefox (Desktop/Android)
- ✅ Opera (Desktop/Android)

## 📈 Améliorations Futures

- [ ] Intégration API backend
- [ ] Notifications Push
- [ ] Mode sombre/clair
- [ ] Galerie photos interactive
- [ ] Système de réservation en ligne
- [ ] Chat en temps réel
- [ ] Partage sur réseaux sociaux
- [ ] Système de favoris

## 📞 Support

Pour toute question ou assistance:
- Email: smoctar729@gmail.com
- Téléphone: +221 77 898 29 25
- Adresse: Liberté 6 Extension, Dakar

## 📄 Licence

© 2026 IMMOLUXE.SN. Tous droits réservés.

---

**Développé avec ❤️ pour IMMOLUXE.SN**
