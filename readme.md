# git
| Git CLI                                       | ohmyzsh aliases        | Description                       |
|-----------------------------------------------|------------------------|-----------------------------------|
| `git version`                                 |                        | check la version de git           |
| `git init`                                    |                        | initialiser un repo               |
| `rm -rf .git`                                 |                        | suprrimer le dossier .git         |
| `git status`                                  |                        | check l'état du repo              |
| `git add nom-de-fichier`                      |                        | ajouter fichier                   |
| `git add --all`                               | `gaa`                  | ajouter tous les fichiers         |
| `git commit -m "commentaire"`                 | `gcmsg`                |                                   |
| `git log`                                     | `gclgg`                | historique des versions           |
| `git checkout nom-de-branche`                 | `gco nom-de-branche`   | se positionner sur la branche     |
| `git reset --hard`                            | `grhh`                 | retour arrière commit précédent   |
| `git remote add origin http//github.com/...git` | `gra origin ...`     | ajouter origine                   |
| `git remote rm origin`                        |                        | suppr origine                     |
| `git remote -v`                               |                        | check remote                      |

## Create branch
| Git CLI                                    | ohmyzsh aliases       | Description                                                         |
|--------------------------------------------|---------------------|---------------------------------------------------------------------|
| `git checkout dev`                         | `gco dev`           | se positioner sur la branche dev locale                             |
| `git pull origin dev`                      | `ggpull`            | pour récupérer de GitHub la dernière version de dev sur github      |
| `git branch`                               | `gb`                | affiche toutes les branches de ton repo Git local                   |
| `git branch nom_de_feature`                |                     | créé une branche portant pour nom "*nom_de_feature*"                |
| `git checkout nom_de_branche`              |                     | se positionne sur la branche qui s'appelle "*nom_de_branche*"       |
| ---- NE PAS FAIRE ----                     |                     |                                                                     |
| `git branch -d nom_de_branche`             | `gbd`               | supprimer branche                                                   |


## Merge branch
| Git CLI                                | ohmyzsh aliases         | Description                                                |
|----------------------------------------|-----------------------|------------------------------------------------------------|
| `git checkout dev`                     | `gco dev`             | te remets sur la branche dev                               |
| `git pull origin dev`                  | `ggpull`              | récupère de GitHub et mets la branche dev à jour           |
| `git checkout nom_de_branche`          | `gco nom_de_branche`  | te remets sur ta branche pour la fusionner                 |
| `git merge dev`                        |                       | fusionne dev dans ta branche. **gestion de conflits**      |
| `git checkout dev`                     |                       | te remets sur dev                                          |
| `git merge nom_de_ta_feature`          |                       | fusionne ta branche DANS dev. **gestion de conflits**      |
| `git push origin dev`                  |                       | met GitHub à jour                                          |
