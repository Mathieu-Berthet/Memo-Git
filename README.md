Apprentissage des commandes suivante : 
git add : Pour ajouter un fichier dans la Staging Area
git commit : Pour envoyer un fichier sur git
git status : pour afficher le status des fichiers. Rouge : Pas encore en staging / Vert : Prêt a être commit
git log : Pour afficher les commits
git checkout : pour se déplacer sur les branches.
git push : Pour envoyer sur le travail sur un dépot distant





Detached Head, Qu'est ce que c'est et pourquoi ce n'est pas souhaitable : 
- C'est quand on fait un checkout sur un commit qui n'est pas le head principal, puis qu'on fait un commit depuis ce dernier. 
Tout les commit fait depuis celui ci ne seront ensuite pas garder par Git. C'est donc pour cela que ce n'est pas souhaitable.




Résolution de conflits : 
- Si les repos local et distants sont divergeants après avoir pull le repo distant, alors qu'on a fait des modifications en local, on a un conflit. 
Pour le résoudre, on peut ouvrir le/les fichiers correspondants via la ligne de commande (ou a l'aide d'un éditeur graphique) et choisir les modifications qu'on veut garder ou non. Une fois fini, on peut renvoyer le fichier avec les modifications effectués. Le conflit est alors résolu. 
