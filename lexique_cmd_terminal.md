### 06/01/2020 et 07/01/2020 - Laurent Hubert

# Linux et environnement développeur

Une fois par jour, dans le terminal, il faudrait faire :
`sudo apt update` pour mettre à jour.

  Si un fichier ou un dossier commence par un `.` alors il est caché par défaut.

## Liste des commandes qu'on peut écrire dans le terminal

`.` dossier actuel

`~` home

`->` lien symbolique

`apropos` liste d'aide des commandes (ex: apropos copy)

`apt-cache search` rechercher un mot spécifique pour quand on ne connaît pas le nom exact du paquet à installer

`cat` afficher le contenu d'un **fichier**   (un peu comme `less`)

`cd` change directory (changer de répertoire)

`cd /` racine de fichiers

`cd ..` remonter d'un répertoire

`cd ../` aller dans un dossier situé dans le même répertoire que le dossier actuel

`cd -` revenir dans le répertoire dans lequel j'étais juste avant

`clear` 'vider' le terminal (pour quand on y voit plus rien)

`cp` copier

`dir` lister  (// `ls`)

`git` donne la liste de commandes GIT

`less` afficher le contenu d'un fichier (comme `cat`) mais **sans le modifier**

`ll`   = `ls -l`  lister en détails

`ln` créer un lien vers un fichier

`ln -s` créer un lien **symbolique** vers un fichier

`ls` lister les fichiers et dossiers présents dans le répertoire  (= `dir`)

`ls -a` afficher les fichiers et dossiers **cachés**

`ls -l` lister en détails

`man` plus de détails, manuel d'aide

`mkdir` make directory (créer un dossier)

`mv` déplacer (prend 2 arguments: source et cible)

`nano` éditer les fichiers

`pwd` print working directory (afficher le dossier dans lequel on se trouve actuellement)

`rm` supprimer

`rmdir` supprimer le dossier

`rm -r` supprimer le dossier de manière récursive (tous les sous-dossiers aussi)

`sudo` super utilisateur

`sudo less /etc/shadow` afficher le contenu du fichier qui contient le mot de passe utilisateur (mais ce contenu est "hashé" et "salé" : on ne peut pas vraiment voir le MDP)

`sudo nano` éditer les fichiers en tant que super-utilisateur (root)

`sudo reboot` redémarre l'ordinateur

`sudo rm -rf /` supprime **tous les fichiers** donc à NE JAMAIS FAIRE !!! (sinon ordi poubelle)

`sudo su -`  root



`touch` créer un **fichier**

`tree` afficher l'arborescence (il faut installer cette commande)

## Liste des raccourcis claviers du terminal

`CTRL + C` arrêter ce qui se passe dans le terminal

`CTRL + D` déconnexion de la console

`CTRL + W` effacer tout ce qui est écrit entre curseur et l'espace précédente

`Q` quitter (le manuel)

# utilisateurs et droits d'accès POSIX

Quand on tape la commande `ls -l`, la liste s'affiche et la colonne de gauche reprend les droits d'accès de chaque fichier/dossier, répartis en 3 catégories :

`t` type de fichier

`u` owner user (utilisateur)

`g` group

`o` other users

`r` read

`w` write

`x` execution

### les types de fichiers
`-` socket

`d` directory

`s` socket

`b` block device (c'est le **noyau** qui écrit dans ce type de fichiers)

`c` character device

`p` FIFO (first in first out) = tuyau, tube, pipe

# titre de folie
```javascript
console.log("Hello");




```



```css
h2 {
  color:red;
  font-size: 100px;  
}

```
