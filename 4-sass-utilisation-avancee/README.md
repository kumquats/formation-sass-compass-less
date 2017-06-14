## Objectifs
Réorganiser le code avec les partials et les imports, mettre en place un mécanisme de thème permettant de changer rapidement les couleurs de la page grâce aux mixins. Rendre la page responsive grâce aux media queries.

## Instructions
1. répartir le code du fichier application.scss en plusieurs fichiers/partials (1 partial par partie de la page). 
2. créer un mécanisme de thème permettant de changer la palette de couleurs du site en changeant simplement la classe du body
3. ajouter des media queries permettant de changer le mode d'affichage des boutons sur smartphone et tablette portrait (largeur d'écran inférieure à 768px) : pour ces périphériques les boutons doivent s'afficher les uns en dessous des autres et prendre toute la largeur de la page.






Utilisation de LiveReload pour actualisation auto du navigateur à l'enregistrement des sources

Installation de [Node.js](https://nodejs.org/en/download/)

Installation de l'extension [LiveReload pour Chrome](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei)

Installation de Gulp et modules complémentaires

```cmd
npm init
npm install --global gulp-cli
npm install --save-dev gulp gulp-live-server gulp-livereload gulp-load-plugins gulp-sass
```
