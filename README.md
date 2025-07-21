

Dérivation numérique et extrapolation de Richardson

** Objectif du projet **
Ce projet a pour but de comparer différentes approches d’approximation de la dérivée d’une fonction, en mettant en évidence les erreurs numériques liées au choix du pas, ainsi que l’amélioration possible grâce à l’extrapolation de Richardson.

** Contexte **
La dérivation numérique repose sur des schémas d’approximation (comme la méthode des différences finies). Ceux-ci dépendent d’un paramètre crucial : le pas ℎ. 
Un mauvais choix de ℎ peut entraîner :
Une erreur de troncature si ℎ est trop grand.
Une erreur d’arrondi si ℎ est trop petit (effet des limites de la précision machine).

** Ce projet vise à ** :
Étudier expérimentalement ces erreurs.
Montrer comment l’extrapolation de Richardson permet de réduire l’erreur en combinant plusieurs approximations.

** Contenu du dépôt **
derivee_centrale.m : fonction qui calcule la dérivée via la méthode centrale.
richardson.m : implémente l’extrapolation de Richardson.
main.m : script principal qui effectue les comparaisons sur différentes fonctions et tailles de pas.
rapport.pdf : analyse complète des résultats avec graphiques, courbes d’erreurs, et commentaires.

** Résultats observés **
L’erreur suit une courbe en U selon la taille de  ℎ, ce qui illustre le compromis entre troncature et arrondi.
L’extrapolation de Richardson permet d’obtenir un meilleure précision pour une large gamme de valeurs de ℎ.
Les courbes d’erreur sont disponibles dans rapport.pdf.
