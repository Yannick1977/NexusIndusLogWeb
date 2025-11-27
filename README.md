# NexusIndusLogWeb

Site web officiel pour NexusIndusLog - Solution de collecte, historisation et visualisation de données industrielles.

## 🌐 À propos

NexusIndusLog est un outil permettant de :
- **Se connecter à des équipements industriels** via différents protocoles
- **Historiser les données** collectées en temps réel
- **Visualiser les variables** en temps réel et dans l'historique

Ce site web présente NexusIndusLog et permet aux utilisateurs de télécharger le logiciel.

## ✨ Fonctionnalités du logiciel

- **Collecte multi-équipements** : Connexion simultanée à plusieurs équipements industriels
- **Export de données** : Export en plusieurs formats (CSV, Excel, JSON)
- **Visualisation temps réel & historique** : Graphiques dynamiques et analyse des tendances

## 📁 Structure du projet

```
NexusIndusLogWeb/
├── index.html          # Page d'accueil principale
├── download.html       # Page de téléchargement détaillée
├── 404.html            # Page d'erreur personnalisée
├── .nojekyll           # Désactive Jekyll sur GitHub Pages
├── styles.css          # Styles CSS (thème sombre bleu)
├── script.js           # JavaScript (interactions et animations)
└── README.md           # Ce fichier
```

## 💻 Plateformes supportées

| Plateforme | Version | Configuration requise |
|------------|---------|----------------------|
| Windows | 25.0 | Windows 10/11 (64-bit) |
| Linux Ubuntu | 25.0 | Ubuntu 20.04+ |

## 🚀 Déploiement sur GitHub Pages

### Configuration

1. Allez dans **Settings** de votre dépôt GitHub
2. Dans le menu latéral, cliquez sur **Pages**
3. Sous "Source", sélectionnez la branche `main` et le dossier `/` (root)
4. Cliquez sur **Save**
5. Votre site sera disponible à : `https://yannick1977.github.io/NexusIndusLogWeb/`

### Test local

```bash
# Option 1 : Avec Python
python -m http.server 8000

# Option 2 : Avec Node.js (npx)
npx http-server

# Option 3 : Avec PHP
php -S localhost:8000
```

Puis ouvrez votre navigateur à : `http://localhost:8000`

## 🎨 Personnalisation

### Thème de couleurs (Sombre bleu)

Les variables CSS dans `styles.css` :

```css
:root {
    --primary-color: #3b82f6;
    --secondary-color: #2563eb;
    --accent-color: #60a5fa;
    --dark-bg: #0f172a;
    --darker-bg: #020617;
    --card-bg: #1e293b;
}
```

### Ajouter des liens de téléchargement

Dans `download.html`, remplacez les `#` par vos vrais liens :

```html
<a href="https://github.com/Yannick1977/NexusIndusLog/releases/download/v25.0/setup.exe" 
   class="btn btn-primary">
    Télécharger (64-bit)
</a>
```

## 📱 Responsive Design

Le site est optimisé pour tous les appareils :
- **Desktop** : Layout complet avec grilles multi-colonnes
- **Tablette** : Adaptation automatique des grilles
- **Mobile** : Menu hamburger et layout en colonne unique

## 🔧 Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styles modernes (Grid, Flexbox, animations)
- **JavaScript** - Interactions et animations
- **Google Fonts** - Police Inter

## 📞 Support

- **Documentation** : [GitHub Wiki](https://github.com/Yannick1977/NexusIndusLogWeb/wiki)
- **Issues** : [GitHub Issues](https://github.com/Yannick1977/NexusIndusLogWeb/issues)
- **Discussions** : [GitHub Discussions](https://github.com/Yannick1977/NexusIndusLogWeb/discussions)

---

© 2025 NexusIndusLog. Tous droits réservés.