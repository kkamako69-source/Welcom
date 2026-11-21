# Morning Starr Morgan — version alternative

Ce dépôt contient une autre version de la page **Morning Starr Morgan | Official**.

## Contenu
- `index.html` : page HTML autonome, avec des liens sociaux et des éléments interactifs.
- La page charge une bibliothèque QR Code depuis jsDelivr.

## Attention aux doublons
Le dépôt `Morning_Starr-pro` contient aussi le site artistique et correspond au site publié connu : https://kkamako69-source.github.io/Morning_Starr-pro/

Avant de modifier cette copie, déterminer si elle est une maquette, une sauvegarde ou une autre version à publier. Ne supprimer ni fusionner les deux dépôts avant comparaison et sauvegarde.

## Vérification
Ouvre `index.html` dans un navigateur, teste les liens et interactions, puis contrôle le rendu mobile avant toute publication.

> État documenté : version à comparer avec le dépôt principal ; son rôle exact reste à confirmer.

## Contrôle automatique

Le contrôle de structure HTML peut être lancé localement avec :

```sh
python tools/check_site.py
```

GitHub Actions lance aussi ce contrôle à chaque modification de la branche `main` et pour chaque pull request. Les avertissements (par exemple un fragment HTML ou une ressource locale introuvable) doivent être examinés ; un passage réussi ne remplace pas les tests dans un vrai navigateur.
