# codex-prime

Site statique HTML/CSS/JavaScript prévu pour être publié sur Cloudflare Pages, à partir de la branche `main`.

## Pages

- `index.html` : accueil
- `outils.html` : sélection d’outils et recherche/filtrage côté navigateur
- `aide.html` : aide à la navigation
- `info-site.html` : présentation et statut d’accessibilité
- `donnees-personnelles.html` : cookies et données personnelles
- `mentions-legales.html` : mentions légales à compléter avant d’affirmer leur conformité juridique

## Présentation et navigation

- `style.css` : styles de l’accueil et des pages d’information
- `site-footer.css` : style partagé du pied de page
- Le même pied de page HTML statique est recopié dans les six pages. Toute modification des liens doit être reportée sur les six pages.
- La page `outils.html` conserve ses styles spécifiques intégrés.

## Confidentialité et ressources

Aucun traceur, script distant, police distante ou cookie de suivi n’est ajouté dans les sources. Les liens vers des domaines externes sont des liens de navigation et non des chargements automatiques. L’hébergement Cloudflare peut traiter des données techniques indépendamment des sources du site. Les informations légales incomplètes sont explicitement signalées.

## Développement

Ouvrir `index.html` localement dans un navigateur. Aucun processus de compilation ni installation de dépendances n’est nécessaire.
