
# terminal
+ `man` permet de lancer le manuel des fonctions.
+ `pwd` affiche le dossier dans lequel tu es actuellement.
+ `ls` est une commande qui affiche les fichiers et dossiers contenus dans mon dossier actuel.
+ `mkdir` permet de créer un dossier.
+ `cd` permet de changer de dossier.
+ `touch` permet de créer un fichier.
+ `cp` permet de copier un fichier.
+ `mv` permet de déplacer un fichier ou un dossier.
+ `rm` permet de supprimer un fichier.
+ `rm -r` permet de supprimer un dossier et son contenu.

# git
+ `git --version` check la version de git installée.
+ `git init` initaliser un repository.
+ `rm -rf .git` suprrimer le dossier .git
+ `git status` check l'état du repo
+ `git add *nom-de-fichier*` ajouter fichier
+ `git commit -m "commentaire"`
+ `git log` historique des versions
+ `git checkout *SHA*` retour arrière à titre indicatif (*SHA*: code commit) /!\ ne fonctionne que si toutes modifs commit
+ `git checkout master` retour version actuelle
+ `git reset --hard *SHA*` retour arrière 
+ `git reset --hard` retour arrière commit précédent

# github
+ `git remote add origin https://github.com/username/file.git`
+ `git remote -v` check remote
+ `git branch -m main` nouvelle branche
+ `git push origin main` push branche *main* vers remote *origin*