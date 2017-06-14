# TP - Sass les bases : premier projet Sass

## Objectifs
Convertir en SASS un projet existant codé en CSS.

## Préparatifs
1. Récupérer les fichiers du repository (clone ou téléchargement zip) depuis : https://github.com/kumquats/formation-sass-compass-less/tree/master/2.2-projet-sass
2. S'assurer que votre machine dispose d'un serveur Apache. Dans le cas contraire, télécharger et Installer Apache, PHP et MySQL à l'aide de [Xampp](https://www.apachefriends.org/fr/index.html), ou une autre solution packagée comme [WAMP](http://www.wampserver.com/) ou [MAMP](https://www.mamp.info/en/).

## Instructions
1. Modifier le fichier scss/application.scss pour y ajouter une css de normalize : cf. https://github.com/necolas/normalize.css/blob/master/normalize.css . Compiler et tester que la css a correctement été compilée en chargeant votre page index.html dans un navigateur
2. Pour plus de simplicité par la suite dans la gestion des width et des paddings, ajouter la règle :
    ```css
    - {
        -moz-box-sizing: border-box;
        box-sizing: border-box;
    }
    ```
3. En inspectant le code HTML et les règles CSS qui s'appliquent aux différents éléments de la page http://treehouse-code-samples.s3.amazonaws.com/poly/index.html ajouter dans le fichier scss les règles SASS nécessaires pour définir :
    - la couleur et la police de caractères des textes
    - le style des balises de titres, des liens, des paragraphes, des blockquotes
    - le style des boutons et des champs de formulaire
    - le styles des progress bars et des images
    - le style des deux navigations (tabs et off-canvas menu)
Utiliser l'imbrication, les variables, le sélecteur parent.
A ce stade ne pas gérer la grille et l'affichage sur plusieurs colonnes (les classes grid, et grid__* seront écrites dans un prochain TP) : les 2 formulaires s'affichent l'un en dessous de l'autre et prennent chacun toute la largeur de la page.
Seul le fichier scss peut être modifier (pas de modification du fichier index.html :smile_cat: ).
