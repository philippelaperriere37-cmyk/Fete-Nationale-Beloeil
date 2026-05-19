# Design d'organisation - Page Web d'evenement

## Objectif

Preparer une base de projet statique pour une page Web d'evenement a venir.

## Decision retenue

Utiliser une structure HTML, CSS et JavaScript simple, avec des dossiers separes pour les actifs, le style, les scripts, le contenu et la documentation.

## Architecture

- `test 1.html` contient la structure principale de la page.
- `css/main.css` contient les styles globaux.
- `js/main.js` contient les comportements simples.
- `assets/` regroupe les images, icones et polices.
- `content/` conserve les notes nettoyees et les sources issues de Gmail.
- `docs/` conserve le brief et les decisions de projet.

## Flux de contenu Gmail

Les informations importantes seront d'abord resumees dans `content/source-emails.md`, puis transformees en contenu exploitable dans `content/event-notes.md`. La page sera ensuite mise a jour a partir de ces notes.

## Portee actuelle

La structure initiale inclut des textes temporaires et des sections attendues pour une page d'evenement : accueil, details, programme, infos pratiques et contact. Le design visuel final sera decide apres l'extraction des details reels.

## Verification

La verification initiale consiste a confirmer que les fichiers existent, que la page statique peut s'ouvrir localement et que l'organisation reste facile a modifier.
