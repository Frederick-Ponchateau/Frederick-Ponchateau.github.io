# Site CV (Frederick-Ponchateau.github.io)

CV en ligne de Fred (développeur web et mobile), publié sur GitHub Pages : https://frederick-ponchateau.github.io/

## Stack
- Site statique, une seule page : `index.html` (HTML + Bootstrap 4, jQuery, Now UI Kit, AOS, Font Awesome, tout en local dans `public/`).
- Pas de build, pas de dépendances à installer. Déploiement : push sur la branche principale = mise en ligne par GitHub Pages.

## Commandes (vérifiées le 2026-10-16)
- `python3 -m http.server 8811` puis http://localhost:8811 : aperçu local.

## Où sont les choses
- Contenu du CV : tout dans `index.html`. Styles perso : `public/css/main.css`. Script : `public/scripts/main.js`.
- CV PDF téléchargeable : `public/document/CV-Frederick-Ponchateau.pdf` (bouton avec l'attribut `download`).
- SEO : `robots.txt`, `sitemap.xml` (penser à mettre à jour `lastmod`).
- `public/index.php` : reste d'un ancien projet CodeIgniter, inutilisé sur GitHub Pages (à confirmer avant de supprimer).

## Conventions
- Textes en français, pas de tirets cadratins (document destiné à être envoyé).
- Pas de mention de marques d'IA dans les fiches projets.
- Garder le contenu cohérent avec le PDF du CV et avec le site FetchDev (~/dev/fredtech).

Contexte long, décisions et état : voir ~/dev/vault-fred/02-Projets/Site-CV/Site-CV.md
