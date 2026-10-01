# Rayoco · Assemblage

Identité basée sur le concept approuvé : deux pièces géométriques assemblées, un symbole orange et un nom dessiné en bleu marine. Les SVG contiennent des tracés, sans police ni image incorporée.

## Fichiers

- `rayoco-logo.svg` et `.png` : orange et marine, sur fond clair.
- `rayoco-logo-reversed.svg` et `.png` : orange et blanc, sur fond sombre.
- `rayoco-logo-monochrome.svg` et `.png` : version marine monochrome.
- `rayoco-logo-white.svg` et `.png` : version blanche monochrome.
- `rayoco-mark.svg` : symbole orange seul.
- `rayoco-mark-white.svg` : symbole blanc seul.

Les PNG sont transparents, de 2 220 px de large. Les SVG sont utilisables à toute taille. Les favicons, le fichier ICO et les icônes pour téléphone se trouvent à la racine des fichiers publics de l’application.

## Utilisation

Orange : `#F9701B`. Marine : `#152633`. Blanc : `#FFFFFF`.

Conserver les proportions. Utiliser la version orange et blanche sur fond marine. Préserver un espace libre autour du logo d’au moins la moitié de la largeur du symbole. Utiliser le symbole seul quand le nom serait trop petit pour être lu.

Les sources vectorielles sont centralisées dans `scripts/brand-source.mjs`. Le script `scripts/generate-brand-assets.mjs` produit les déclinaisons et les icônes avec Sharp.
