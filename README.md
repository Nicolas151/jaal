# JAAL Rituel Beauté

Site vitrine statique pour **JAAL**, Maison de rituels beauté inspirée des
traditions ancestrales du Maroc : soin & massage facial holistique à domicile.

## Structure

```
.
├── index.html          Page unique du site (toutes les sections)
├── style.css           Feuille de styles (palette, typographie, mise en page)
├── script.js           Menu mobile, animations au scroll, formulaire de contact
├── assets/
│   └── img/            Logo et photos optimisées pour le web
└── README.md
```

## Développement local

Aucune installation n'est nécessaire. Ouvrez simplement `index.html` dans un
navigateur, ou lancez un petit serveur local pour un rendu identique à la
production :

```bash
python3 -m http.server 8000
```

Puis rendez-vous sur `http://localhost:8000`.

## Déploiement sur GitHub Pages

1. Poussez ce dossier sur la branche `main` d'un dépôt GitHub.
2. Dans **Settings → Pages**, choisissez la branche `main` et le dossier `/root`.
3. Le site est publié automatiquement à l'adresse fournie par GitHub.

## Modifier le contenu

- **Textes** : directement dans `index.html`, section par section (chaque
  section est identifiée par un commentaire `<!-- ===== NOM ===== -->`).
- **Couleurs / typographies** : variables au tout début de `style.css`
  (bloc `:root`).
- **Images** : ajoutez vos fichiers dans `assets/img/` puis mettez à jour le
  chemin correspondant dans `index.html`. Privilégiez des images déjà
  compressées (format `.jpg`, largeur ≤ 1600px) pour conserver un site rapide.

## Contact affiché sur le site

- Email : jaal.rituel.beaute@gmail.com
- Téléphone : +33 (0)6.79.18.10.83
- Instagram : [@jaal.rituel.beaute](https://www.instagram.com/jaal.rituel.beaute)
