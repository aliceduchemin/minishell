# minishell

Création d'un shell en C

- Aucune librairie autorisée
- Gestion de la mémoire (aucune fuite de mémoire autorisée)
- Gestion des commandes chaînées
- Gestion des pipes ( | )
- Gestion des single quotes ( ' ) et double quotes ( " )
- Gestion des redirections (<, >, <<, >>)
- Gestion des variables d'environnement
- Gestion des exit status ( $? )
- Gestion des signaux (ctrl-C, ctrl-D, ctrl-\)
- Implémentation des fonctions builtins suivantes :
 - echo (avec option -n)
 - cd (avec chemin relatif ou absolu)
 - pwd
 - export
 - unset
 - env
 - exit
