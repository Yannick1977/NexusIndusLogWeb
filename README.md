# NexusIndusLogWeb

Site web officiel pour NexusIndusLog - Solution de gestion industrielle moderne et performante.

## 🌐 À propos

Ce site web présente NexusIndusLog et permet aux utilisateurs de télécharger le logiciel. Il est conçu pour être simple, élégant et entièrement responsive.

## ✨ Fonctionnalités du site

- **Page d'accueil** avec présentation du logiciel
- **Section fonctionnalités** détaillant les capacités du logiciel
- **Section téléchargement** pour toutes les plateformes (Windows, macOS, Linux)
- **Page dédiée** aux téléchargements avec guides d'installation
- **Design moderne** et responsive (mobile, tablette, desktop)
- **Animations fluides** et expérience utilisateur optimisée
- **Prêt pour GitHub Pages** - déploiement facile

## 📁 Structure du projet

```
NexusIndusLogWeb/
├── index.html          # Page d'accueil principale (page par défaut)
├── download.html       # Page de téléchargement détaillée
├── 404.html            # Page d'erreur personnalisée
├── .nojekyll           # Désactive Jekyll sur GitHub Pages
├── styles.css          # Styles CSS (design moderne et responsive)
├── script.js           # JavaScript (interactions et animations)
└── README.md          # Ce fichier
```

## 🚀 Déploiement sur GitHub Pages

### Configuration de la page par défaut

✅ Le fichier `index.html` est automatiquement reconnu comme page par défaut par :
- GitHub Pages
- Tous les serveurs web standards (Apache, Nginx, etc.)
- Les navigateurs locaux

**Fichiers de configuration inclus :**
- `.nojekyll` : Désactive le traitement Jekyll sur GitHub Pages
- `404.html` : Page d'erreur personnalisée qui redirige vers l'accueil

### Méthode automatique

1. Allez dans **Settings** de votre dépôt GitHub
2. Dans le menu latéral, cliquez sur **Pages**
3. Sous "Source", sélectionnez la branche `main` et le dossier `/` (root)
4. Cliquez sur **Save**
5. Votre site sera disponible à : `https://yannick1977.github.io/NexusIndusLogWeb/`

### Test local

Pour tester le site localement avant le déploiement :

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

### Modifier les couleurs

Éditez les variables CSS dans `styles.css` :

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --dark-color: #1a202c;
    /* ... */
}
```

### Ajouter des liens de téléchargement

Dans `download.html`, remplacez les `#` par vos vrais liens :

```html
<a href="https://github.com/Yannick1977/NexusIndusLog/releases/download/v1.0.0/setup.exe" 
   class="btn btn-primary">
    Télécharger (64-bit)
</a>
```

### Modifier le contenu

- **Textes** : Éditez directement dans `index.html` et `download.html`
- **Images** : Ajoutez vos images dans un dossier `/images` et référencez-les
- **Sections** : Ajoutez/supprimez des sections selon vos besoins

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

## 📝 À faire après déploiement

1. ✅ Ajouter vos vrais fichiers de téléchargement (releases GitHub)
2. ✅ Personnaliser les textes selon votre logiciel
3. ✅ Ajouter des captures d'écran du logiciel
4. ✅ Configurer Google Analytics (optionnel)
5. ✅ Ajouter un fichier `CNAME` si vous utilisez un domaine personnalisé
6. ✅ Créer une section documentation ou wiki

## 🔒 Sécurité

- Pas de dépendances externes (sauf Google Fonts)
- Code statique - pas de backend requis
- Hébergement sécurisé via GitHub Pages (HTTPS)

## 📄 Licence

Ce site web est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Ouvrir une issue pour signaler un bug
- Proposer des améliorations
- Soumettre une pull request

## 📞 Support

- **Documentation** : [GitHub Wiki](https://github.com/Yannick1977/NexusIndusLogWeb/wiki)
- **Issues** : [GitHub Issues](https://github.com/Yannick1977/NexusIndusLogWeb/issues)
- **Discussions** : [GitHub Discussions](https://github.com/Yannick1977/NexusIndusLogWeb/discussions)

---

Développé avec ❤️ pour la communauté NexusIndusLog