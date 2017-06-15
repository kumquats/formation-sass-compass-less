# TP Bonnes pratiques

## Instructions
1. Organiser les fichiers scss dans des sous-répertoires
    - utilities : Stocke la configuration, les fonctions, helpers et mixins
    - base : Contient les styles de base et les CSS de reset ou  normalize
    - layout : Styles permettant de définir les layouts du site
    - modules : Styles des différents modules du site
    - states : Styles des différents états des modules du site
    - themes : Styles des différents thèmes du site
2. Optimiser le code et le temps de chargement/rendu en minifiant la css générée
    ```ruby
    # Dans le fichier config.rb
    # Activation de la compression des CSS
    output_style = :compressed
    ```