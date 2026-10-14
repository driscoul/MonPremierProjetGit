# Description du projet
## initialisation du projet

``` bash

git init
git remote add origin SSH_REPO
```
## Rediger un commit (Bonne pratique)

Titre du commit

Description de notre commit avec des informations sur l'evolution du projet

## Envoyer un commit sur le depot distant

``` bash
git add . 
git commit -m "Titre du commit"
git push origin main
```
## Creer une nouvelle Branch

````bash
    git checkout -b NOM_DE_LA_BRANCHE
````
Pour les bonnes pratiques on va utiliser la notion de revue de code. Pour cela, on va creer une branche, faire des modifications, les envoyer vers le depot distant, puis creer une pull request( sur GITHUB) pour demander une revue de code.
