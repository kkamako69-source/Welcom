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

> État documenté au 24 novembre 2026 : copie alternative et non canonique. Les corrections géographiques et de liens sociaux y sont maintenues pour éviter d'afficher des informations trompeuses, mais les nouvelles évolutions doivent être réalisées dans le dépôt principal.

## Contrôle automatique

Le contrôle de structure HTML peut être lancé localement avec :

```sh
python tools/check_site.py
```

GitHub Actions lance aussi ce contrôle à chaque modification de la branche `main` et pour chaque pull request. Les avertissements (par exemple un fragment HTML ou une ressource locale introuvable) doivent être examinés ; un passage réussi ne remplace pas les tests dans un vrai navigateur.

## Rôle de ce dépôt

Cette version est conservée comme copie alternative. La balise canonical pointe vers le site principal [Morning_Starr-pro](https://kkamako69-source.github.io/Morning_Starr-pro/). Effectue les mises à jour sur le dépôt principal pour éviter de maintenir deux versions en parallèle.

## Sécurité et qualité

Les contrôles HTML/JavaScript et CodeQL s'exécutent via GitHub Actions. Dependabot surveille les actions GitHub chaque semaine. La page reste une copie alternative ; la source éditoriale officielle est `Morning_Starr-pro`.
