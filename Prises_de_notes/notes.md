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
```
Pour pousser les fihcier vers github, il suffit de créer un répertoire et le lignes de commandes son directement données pour chaque répertoires.

## HTML/CSS

HTML : structure

CSS : Visuel 

JAVA: comportement

site aide : https://developer.mozilla.org/fr/docs/Web/CSS

Live server permet de suivre l’évolution de sa page web en temps réel. 

Les balises 
une balise est composer d’une partie ouvrante et fermante :

	```html
	<p> contenu </p> texte
	```

Le balises qui n’ont pas de continu ne sont pas destiné à avoir du contenu :

	```
	<hr> — ligne
	<img> — image
	```
La balise ```<P>``` est destiné à afficher du texte.

Chaque élément HTML peut avoir des attributs :
	```
	<p id=« test »> ceci est un un pargraphe </p>
	```

Ajouter un commentaire :
```
<!- - texte - - >
```

### Structure des pages web :


élément ```<head>``` permet de mettre des meta données ou le titre de la page web 

L’élément ```<html>``` est l’élément racine des pages HTML

L’élément head : 
	Il contient des propriétés  essentiels pour les pages web.
	Chacune de ces propriétés est renseignes avec des élements « enfant ». 
	Title est obligatoire dans la balise <Head>

Tout le contenu qui s’affiche sur la page web doit être contenu dans la balise ```<Body>```

Conception d’une page WEB :
Nous devons réfléhir en termes de conteneur. Un conteneur inclut des éléments très variés.
Le conteneur sert à structurer sa page

Il faut éviter d’utiliser l’élément div bien que cela ne soit pas pénaliser. 

l’élément SPAN
Il est utiliser pour appliquer du style à un endroit précis.

l’élément header 

permet d’afficher une zone d’affichage en-tête par exemple

l’élément footer 
est le pied de la pages (mention légal, réseaux sociaux etc)

l’élément nav : 
Permet de scroll automatiquement. 

l’elément main :
indique le contenu principal de la page. 

l’elément section :

element 

Le role du CSS 
est d’adapter le contenu multimédia à tout les support ou l’ont peut consulter la page HTML.
On peut appliquer du style à certains éléments à l’aide de l’attribut classe . En CSS on cible les elements dont la classe est le test de la manière suivante.
On peut également en CSS appliquer du style de manière spécifique grace a l’attribut html id: 
	
Structure et règles du CSS

Ceci est une règle de style : 
```
selecteur {

	props: valeur

}
```

Le sélecteurs :
	-ne doivent pas commencer par un chiffre
	-ne peuvent pas contenir d’espace, de caractères spéciaux (sauf  « - » et « _ »), de caractères avec des accents
	-sont sensibles à la casse (majuscule/minuscule)

## Flexbox

Flexbox est une méthode de mise en page qui permet d'ajutser les éléments de son site en fonction d'un axe. Grâce à cel on peut les placer en ligne, colone. En fonction de la taille de l'écran ou de la fenêtre les éléments s'adaptent à l'affichage. 