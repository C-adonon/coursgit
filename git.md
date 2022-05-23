# Git 

- Versionning
  - sauvegarder les versions, chronologie
  - permet de revenir en arrière
  - synchronisation
  - collaboratif
  - branches
  
- Utilisation
  - ligne de commande
  - plugin VSC
  - outils bureautique : Github Desktop, TortoiseGit


- Invite de commande : configuration system (voir google)

```
    >
    $
    PATH
    alias
```

- commande:
  - pwd : savoir ou on se trouve
  - mkdir : make directory
  - cd : change directory
  - cd ../../..
  - ls / dir
  - tree : arborescence
  
  - Rediriger la sortie vers un fichier
  - `dir > toto`
  
```
aide:
commande --help
commande -h
command /?

man command

ctrl+c = quitter
```

## Installation

- terminal, console, invite de commande...
- git

## Commencer un projet avec git

```sh
git init .
#U = Untrack

git add README.md
#A = Added

#valider = commit
git commit -am"Premier commit"

#modifier le fichier
#M=modified

git diff
git status

git commit -am"N°2"

#créer .gitignore
# - fichier avec identifiants / mots de passe
# - dossiers temporaires, dossiers dépendances, dossier de compilation


```