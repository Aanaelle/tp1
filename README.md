**Nom :** Anaëlle Mimifir

**Groupe :** A2

**Année :** 2022

**IUT Le Havre - Cours GIT**

### Compte-rendu TP1 Introduction GIT

Dans ce TP on apprend à travailler avec git.


**1. Configuration de GIT**
Dans un premier temps, nous avons configurer GIT avec les commandes :
¤ `git config --global user.name "Anaëlle Mimifir"` : pour configurer le nom de l'utilisateur
¤ `git config --global user.email anaellemimi27@gmail.com` : pour l'addresse mail
¤ `git config --global core.editor Gedit` : pour configurer l'éditeur de texte préféré

Puis pour verifier que tout cela a été pris en compte : 
¤ `git config --list`

**2. Création d’un dépôt git sur une machine locale**
Ensuite nous avons crée un répertoire pour ce premier tp
¤ création des répertoire courseGIT/tp1
¤ `tree courseGIT` : pour vérifier la création des répertoires
¤ `pwd` : même utilité dans le dossier tp1
¤ `ls -a` : pour afficher les dossiers cacher

Puis, nous avons crée notre premier dépôt git :
¤ `git init` : le répertoire tp1 sera géré par git
¤ `ls -a`  : pour vérifier la création du répertoir .git

Afin de vérifier les modifications apportées aux fichiers dans la copie de travail tp1 :
¤ `git status`

**3. Création d’un fichier texte README.md**
Dans cette 3ème partie, nous avons crée le fichier README.md dans l'éditeur de texte
¤ `git status` : pour vir les modifications apportées au dossier
¤ `git add README.md` : permet de garder une trace des modifications du fichier
¤ `git commit -m "Ajoute du fichier README.md"` : ajout du fichier au dépôt
¤ `git log` : permet de voir toutes les versions du fichier


