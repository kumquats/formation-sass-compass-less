# TP Compass

## Objectifs
Gérer les préfixes navigateurs des principales fonctions CSS3, et mettre en place une grille CSS à l'aide de Compass.

## Préparatifs
- Repartir de votre code du TP précédent ou des fichiers de ce dossier (clone ou télécharger le zip) : https://github.com/kumquats/formation-sass-compass-less/tree/master/4-compass
- Installer [Compass](http://compass-style.org/install/)
    ```cmd
    gem install compass
    ```
- Installer [Susy](http://susydocs.oddbird.net/en/latest/install/)
    ```cmd
    gem install susy
    ```
- dans le dossier du projet, lancer la commande pour le configurer  pour utilisation avec compass : 
    ```cmd
    compass init --sass-dir "scss" --css-dir "css" --javascripts-dir "js" --images-dir "img"
    ```
- lancer la commande watch de compass
    ```cmd
    compass watch
    ```


## Instructions
1. remplacer le code de la transition CSS3 sur les boutons par le mixin compass @transition
2. ajouter une animation CSS3 sur les progress bar : la progress bar varie de 0% à 100% puis de 100% à 0%.
3. ajouter une grille susy au projet : centrer les différents contenus et afficher les formulaires sur 2 colonnes comme sur la page de référence de poly.