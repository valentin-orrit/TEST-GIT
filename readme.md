# git

> [!ohmyzsh]
> "// `alias`"

+ `git version` check la version de git
+ `git init` initaliser un repo
+ `rm -rf .git` suprrimer le dossier .git
+ `git status` check l'état du repo
+ `git diff` return les ligne différentes entre le fichier modifié et le précédent commit
+ `git add nom-de-fichier` ajouter fichier
+ `git add --all` // `gaa` ajouter tous les fichiers 
+ `git commit -m "commentaire"` // `gc`
+ `git log` historique des versions
+ `git checkout nom-de-branche` se positionner sur la branche
+ `git checkout SHA` retour arrière à titre indicatif (*SHA*: code commit) /!\ ne fonctionne que si toutes modifs commit
+ `git checkout developpement` retour version actuelle
+ `git reset --hard SHA` retour arrière 
+ `git reset --hard` retour arrière commit précédent

# git collab

## Create branch
+ `git checkout developpement` : se positioner qu'on est bien sur la branche developpement sur son ordi.
+ `git pull origin developpement` : pour récupérer de GitHub la dernière version de developpement.
+ `git branch` : affiche toutes les branches de ton repo Git, puis t'indique sur laquelle tu es actuellement
+ `git branch nom_de_ta_feature` : créé une branche portant pour nom "*nom_de_ta_feature*"
+ `git checkout nom_de_ta_branche` : se positionne sur la branche qui s'appelle "*nom_de_ta_branche*"\
---- NE PAS FAIRE ----
+ `git branch -d nom_de_ta_branche` : supprimer branche

## Merge branch
+ `git checkout developpement` : tu te remets sur la branche developpement en vue de la mettre à jour
+ `git pull origin developpement` : tu récupères de GitHub tout le travail qui a été effectué et mets la branche developpement à jour ;
+ `git checkout nom_de_ta_feature` : tu te remets sur ta branche de feature en vue de la fusionner ;
+ `git merge developpement` : cette commande demande à Git de fusionner developpement dans ta branche. **optionnel : gestion de conflits** 
+ `git checkout developpement` : tu te remets sur developpement
+ `git merge nom_de_ta_feature` : cette fois, on fait la fusion dans l'autre sens. On fusionne ta branche DANS developpement. **optionnel : gestion de conflits**
+ `git push origin developpement` : developpementtenant que la fusion est faite, il faut mettre GitHub à jour pour que tous tes collègues aient l'info.

# github
+ `git remote add origin https://github.com/username/file.git` ajouter origine
+ `git remove rm origin` suppr origine
+ `git remote -v` check remote
+ `git branch -m developpement` nouvelle branche
+ `git push origin developpement` push branche *developpement* vers remote *origin*
______________
# terminal
+ `man` permet de lancer le manuel des fonctions.
+ `pwd` affiche le dossier dans lequel tu es actuellement.
+ `ls` est une commande qui affiche les fichiers et dossiers contenus dans mon dossier actuel.
+ `mkdir` permet de créer un dossier.
+ `cd` permet de changer de dossier.
+ `touch` permet de créer un fichier. // `ni` dans VSCode
+ `cp` permet de copier un fichier.
+ `mv` permet de déplacer un fichier ou un dossier.
+ `rm` permet de supprimer un fichier.
+ `rm -r` permet de supprimer un dossier et son contenu.
