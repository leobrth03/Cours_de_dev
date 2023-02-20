# Dev web

## Git notes diverses 

`cd`est une commande permettant de changer de répertoire.

Renomer une branche : 
```
git branch  -M main
```


La commande :
````
ls -la
````
pemret d'afficher les éléments masqué 

La commande:
```
rm -rf .git/
```
Supprime tout l'historique du répertoire.

commit : C'est l'historique des versions d'un projet que l'on peut également appeler snapshot 

Le depot git ou repository est le dossier qui contient les donnes que l'on souhaite versionner `git/`.

## Création d'un dépot Git

1. On utilise la commande :
    ```
    git init
    ```
Cette commande permet d'initaliser le depot git dans le repertoir local. On retrouve donc un dossier cache en `.git` à la racine du depot. 

2. Pour visualiser l'edition ou l'ajout d'un fichier dans la boite de depot, git le détecte automatiquement on peut le verifier avec la commande :
```
git status
```

3.Pour sauvegarder des modification, il faut ajouter le fichier modifier avec la commande : 

```
git add <nom du fichier>
```

4.Pour suavegarder s'effectue ensuite avec la commande : 
```
git commit -m "<message de commit>"