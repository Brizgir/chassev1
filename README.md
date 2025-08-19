# 🏹 Suivi Chasse - Application PWA

Application de suivi de chasse avec GPS, statistiques et cartographie interactive.

## 📱 Fonctionnalités

- **📊 Suivi des sessions** : Enregistrement détaillé des sessions de chasse
- **🎯 Prélèvements** : Gestion des prélèvements avec photos et notes
- **👁️ Observations** : Suivi des observations d'animaux
- **📍 GPS en temps réel** : Enregistrement des parcours par session
- **🗺️ Points d'intérêt** : Marqueurs pour postes de chasse, points d'eau, etc.
- **📈 Statistiques avancées** : Graphiques interactifs avec Chart.js
- **🖼️ Gestion d'images** : Photos des prélèvements et observations
- **📤 Export/Import** : Sauvegarde et restauration des données
- **📱 PWA** : Installation native sur mobile et desktop

## 🚀 Installation

### Option 1 : GitHub Pages (Recommandé)
1. Clonez ce repository
2. Activez GitHub Pages dans les settings
3. Votre app sera disponible sur `https://votre-username.github.io/votre-repo`

### Option 2 : Hébergement local
```bash
# Serveur simple avec HTTPS
npx http-server -p 8000 --ssl

# Ou avec Python
python -m http.server 8000
```

## 📁 Structure du projet

```
suivi-chasse/
├── suivi-chasse_leaflet_fix_v2.html  # Application principale
├── manifest.json                     # Configuration PWA
├── sw.js                            # Service Worker
├── offline.html                     # Page hors ligne
├── debug-pwa.html                   # Outil de diagnostic
├── generate-icons.html              # Générateur d'icônes
├── README.md                        # Ce fichier
├── README-PWA.md                    # Guide d'installation PWA
├── TROUBLESHOOTING-PWA.md           # Guide de dépannage
└── icons/                           # Icônes PWA
    ├── icon-16x16.png
    ├── icon-32x32.png
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

## 🛠️ Configuration

### 1. Créer les icônes
Ouvrez `generate-icons.html` dans votre navigateur et téléchargez toutes les icônes.

### 2. Vérifier la configuration
Ouvrez `debug-pwa.html` pour diagnostiquer automatiquement votre installation.

### 3. Installer sur mobile
- **Android** : Le bouton "Installer l'app" apparaîtra automatiquement
- **iPhone** : Utilisez "Sur l'écran d'accueil" dans Safari

## 🔧 Dépannage

Si l'application ne fonctionne pas :
1. Ouvrez `debug-pwa.html` pour un diagnostic automatique
2. Consultez `TROUBLESHOOTING-PWA.md` pour les solutions
3. Vérifiez que vous êtes en HTTPS

## 📊 Utilisation

### Créer une session
1. Cliquez sur "Nouvelle Session"
2. Remplissez les informations (date, lieu, météo)
3. Enregistrez la session

### Ajouter des prélèvements
1. Ouvrez une session
2. Cliquez sur "Ajouter Prélèvement"
3. Remplissez les détails et ajoutez des photos
4. Enregistrez

### Enregistrer un parcours GPS
1. Allez dans l'onglet "Carte"
2. Sélectionnez une session
3. Cliquez sur "Démarrer l'enregistrement"
4. Arrêtez et sauvegardez le parcours

### Voir les statistiques
1. Allez dans l'onglet "Statistiques"
2. Utilisez les filtres pour analyser vos données
3. Consultez les graphiques interactifs

## 🔒 Données

- **Stockage local** : Toutes les données sont stockées localement
- **Export** : Sauvegardez vos données en JSON
- **Import** : Restaurez vos données depuis un fichier JSON
- **Privé** : Aucune donnée n'est envoyée sur internet

## 🌐 Compatibilité

- ✅ Chrome (Desktop & Mobile)
- ✅ Edge (Desktop & Mobile)
- ✅ Safari (Desktop & Mobile)
- ✅ Firefox (Desktop & Mobile)

## 📱 Fonctionnalités PWA

- ✅ Installation native
- ✅ Fonctionnement hors ligne
- ✅ Interface native
- ✅ Notifications push (prévu)
- ✅ Synchronisation (prévu)

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des bugs
- Proposer des améliorations
- Ajouter de nouvelles fonctionnalités

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

## 📞 Support

Si vous rencontrez des problèmes :
1. Consultez `TROUBLESHOOTING-PWA.md`
2. Ouvrez `debug-pwa.html` pour un diagnostic
3. Vérifiez la console du navigateur (F12)

---

**🎯 Bonne chasse !** 🏹
