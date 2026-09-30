# Mon Blog

Blog statique en HTML/CSS, hébergé gratuitement sur GitHub Pages.

## Structure

```
mon-blog/
├── index.html              # Page d'accueil
├── css/style.css           # Styles
├── articles/               # Articles du blog
│   ├── mon-premier-article.html
│   └── second-article.html
└── _config.yml             # Config GitHub Pages
```

## Ajouter un article

1. Créer un fichier `articles/nouvel-article.html`
2. Copier la structure d'un article existant comme modèle
3. Ajouter un extrait + lien dans `index.html`
4. Pousser sur GitHub

## Déploiement sur GitHub Pages

1. Créer un dépôt sur GitHub
2. Pousser ces fichiers sur la branche `main`
3. Settings > Pages > Source : `Deploy from a branch` > `main` / `/root`
4. Le site sera disponible sur `https://<username>.github.io/<repo>/`
