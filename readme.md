# git
+ `git --version` check la version de git installée.
+ `git init` initaliser un repository.
+ `rm -rf .git` suprrimer le dossier .git
+ `git status` check l'état du repo
+ `git diff` return les ligne différentes entre le fichier modifié et le précédent commit
+ `git add nom-de-fichier` ajouter fichier
+ `git add --all` ajouter tous les fichiers
+ `git commit -m "commentaire"`
+ `git log` historique des versions
+ `git checkout nom-de-branche` se positionner sur la branche
+ `git checkout SHA` retour arrière à titre indicatif (*SHA*: code commit) /!\ ne fonctionne que si toutes modifs commit
+ `git checkout master` retour version actuelle
+ `git reset --hard SHA` retour arrière 
+ `git reset --hard` retour arrière commit précédent

# git collab

## Create branch
+ `git checkout master` : pour s'assurer qu'on est bien sur la branche master sur son ordi.
+ `git pull origin master` : pour récupérer de GitHub la dernière version de master.
+ `git branch` : affiche toutes les branches de ton repo Git, puis t'indique sur laquelle tu es actuellement
+ `git branch nom_de_ta_feature` : créé une branche portant pour nom "*nom_de_ta_feature*"
+ `git checkout nom_de_ta_branche` : se positionne sur la branche qui s'appelle "*nom_de_ta_branche*"
+ `git branch -d nom_de_ta_branche` : supprimer branche

## Merge branch
+ `git checkout master` : tu te remets sur la branche master en vue de la mettre à jour
+ `git pull origin master` : tu récupères de GitHub tout le travail qui a été effectué et mets la branche master à jour ;
+ `git checkout nom_de_ta_feature` : tu te remets sur ta branche de feature en vue de la fusionner ;
+ `git merge master` : cette commande demande à Git de fusionner master dans ta branche. **optionnel : gestion de conflits** 
+ `git checkout master` : tu te remets sur master
+ `git merge nom_de_ta_feature` : cette fois, on fait la fusion dans l'autre sens. On fusionne ta branche DANS master. **optionnel : gestion de conflits**
+ `git push origin master` : Maintenant que la fusion est faite, il faut mettre GitHub à jour pour que tous tes collègues aient l'info.

# github
+ `git remote add origin https://github.com/username/file.git` ajouter origine
+ `git remove rm origin` suppr origine
+ `git remote -v` check remote
+ `git branch -m main` nouvelle branche
+ `git push origin main` push branche *main* vers remote *origin*
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
