---
layout: post
title: GitHub cheatsheet
---

Git permet gérer des versions de fichiers au sein d'un dossier, grâce à des enregistrements (commits) associés à des commentaires.

`git add .` ajoute l'ensemble des fichiers et des répertoires à l'index de git

`git commit -"commentaire"` permet de faire un enregistrement et d'y associer un commentaire

`git log` permet de voir l'historique des enregistrements pour un dossier donné

`git checkout SHADDuCommit` permet de retourner à un commit

Github permet de sauvegarder les fichiers et leurs évolutions sur un serveur distant.

Sur le site, `fork` permet de copier un dossier github d'un autre utilisateur sur son espace.

Ensuite, `git clone [lien github]` permet de synchroniser un dossier en ligne en local.

A l'inverse, `git push origin main`  permet de synchroniser le dossier en ligne à partir des mises à jour effectuées en local.

Dans le cas du blog, les étapes sont essentiellement : 

1. Création d'un nouvel article dans le dosser `\post` 
2. Se positionner dans le répertoire `\blog` via le terminal
3. `git add .` puis `git commit -m"nouveau post"` puis `git push` 