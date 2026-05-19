# Page Web d'événement

Projet statique pour construire une page Web d'événement.

## Structure

- `test 1.html` : première version de page complète avec structure HTML traditionnelle.
- `test 2.html` : bloc HTML/CSS autonome à coller dans un bloc HTML personnalisé WordPress.
- `css/main.css` : fichier de style conservé pour référence; le bloc WordPress utilise le CSS intégré dans `test 2.html`.
- `js/main.js` : fichier JavaScript conservé pour référence; la version WordPress actuelle n'utilise pas de JavaScript.
- `assets/images/` : photos, visuels et images de l'événement.
- `assets/icons/` : icônes ou pictogrammes.
- `assets/fonts/` : polices locales, si nécessaire.
- `assets/documents/` : documents sources, dont les PDF reçus par courriel.
- `assets/downloads/` : archives et fichiers bruts reçus avant tri.
- `content/event-notes.md` : notes de contenu nettoyées pour la page.
- `content/source-emails.md` : provenance et synthèse des informations tirées de Gmail.
- `docs/brief.md` : brief de travail et décisions de projet.
- `docs/guides/` : synthèses des normes graphiques et linguistiques.

## Source actuelle

- Courriel Gmail du 13 mai 2026 provenant de `plaperriere@beloeil.ca`.
- Pièce jointe : `assets/documents/Beloeil 9X12 FNAT 2026_HIRES.pdf`.
- Courriel WeTransfer du 13 mai 2026 provenant de `noreply@wetransfer.com`.
- Archive : `assets/downloads/wetransfer-2026-05-13/OneDrive_1_13-05-2026.zip`.
- Photos : `assets/images/joyeux-calvaire/`.
- Logos et visuels partenaires : `assets/images/partners/`.
- Guides Ville de Beloeil : `assets/documents/guides/`.

## Prochaine étape

Téléverser les images choisies dans la médiathèque WordPress, puis remplacer les chemins locaux `assets/...` dans `test 2.html` par les URLs de WordPress.

## Intégration WordPress

Le fichier `test 2.html` ne contient volontairement pas de balises `<html>`, `<head>` ou `<body>`. Il est conçu pour être copié tel quel dans un bloc HTML personnalisé.

Les styles sont confinés sous la classe `.fn-beloeil-2026` afin de réduire les risques de conflit avec le thème WordPress.
