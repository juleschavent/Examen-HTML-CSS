Le site a été fait mobile first mais le html a été pensé pour être adapté au desktop car il y a plus de div/flex/grid

Les commentaires en HTML servent à définir les ouvertures et fermetures des balises principales.

La méthode de nommage utilisée est BEM (block, element, modifier)

Reset fait main utilisé au début du CSS et FS à 62.5% pour que 1rem = 10px

Aucune image en BG, que HTML pour optimiser SEO

Je n'ai pas vraiment réussi à faire un CSS DRY car peu de cohérence au niveau de la maquette

Relecture du code une fois le projet terminé pour supprimer les lignes inutiles (type padding alors que la div est en flex). Si il reste quelques propriétés CSS en commentaire c'est que je n'étais pas certain de pouvoir les supprimer sans causer de problème

Je retrouve une alerte sur W3C Validator. Il semblerait qu'il est judicieux d'ajouter des H1, H2 etc. Selon moi et en suivant les bonnes pratiques, la maquette ne permet pas de définir de H1. Plusieurs H2 et H3 ont été utilisés car similaire en importance dans la page.

Objectif personnels :
    => utiliser le moins de div possible
    => prioriser les balises adaptés pour SEO
    => pas de bidouilles type /br etc. Que du code legit
    => utiliser grid ET flex
    => ne pas utiliser shitstrap (bootstrap)
    => utilisation de pseudo element et pseudo class pour optimiser le code