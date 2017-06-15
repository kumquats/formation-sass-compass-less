# TP Less

## Objectifs
Porter un projet sass en less

## Préparatifs
- Repartir de votre code du TP précédent ou des fichiers de ce dossier (clone ou télécharger le zip) : https://github.com/kumquats/formation-sass-compass-less/tree/master/5-less
- Installer [Node.js](https://nodejs.org/en/download/)
- Installer Less
    ```cmd
    npm install less -g
    ```

## Instructions
1. Renommer le dossier scss en less
2. à l'intérieur du dossier less, renommer tous les fichiers pour enlever le underscore et pour changer l'extension des fichiers en .less
3. dans application.less, commenter les imports sauf fonts, normalize, config et base.
4. corriger la syntaxe de ces fichiers pour les rendre compatibles avec less
5. compiler la feuille de styles avec 
    ```cmd
    lessc less\application.less css\application.css
    ```