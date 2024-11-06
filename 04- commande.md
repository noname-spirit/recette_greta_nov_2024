# plus en details

-travail
-git add . 
- git commit -m " "

#git add

git logiciel
add action => snapshot ( prend une photo de toutes les modifications detectée)
- ',' sur tout les fichiers
souvent on veut garder les version que sur un fichier particulier :
remplacer le ',' par un nom du fichier 

- git add
- git add --all
- git add -A

tous els fichiers

git add styll.css

uniquement  le fichier styl.css

# git commit 
modifier le bouton => mettre sur font blue / texte en blanc

message ecrite apres saisit le git commit 

''' txt
[main e7cabbf] mise en forme bouton
 2 files changed, 17 insertions(+), 2 deletions(-)
 '''

 - main => branche principal du projet 
        => la branche == focntionnalité principal du projet 

- e7cabbf => identifiant unique pour la version => le numero de version
        => cet identifiant peut etre ajouté dans trello

mise en forme bouton => message qui est associé au numero de comit 
        => facilité la recherche / distinguer les commit ( version)

- 1 1 gile changed,  insertion(+)
- dans cette version 1 seul fihier modifié et 
- par apport a la version precedente § ligne ajoutées 

# gitk

'''
git log --oneline
'''

id      texte
id      (HEAD -> main) descrption 
e7cabbf (HEAD -> main) mise en forme bouton
0728f1e teste sauvegarde
480cd06 ajustement
77c41d1 misea jour 2
dd1c76c exo1
47e0bc5 mise en page
01aa046 reset css
4ced745 contenu de la 2eme colonne
6310025 contenu premiere colonne
b4f92ef création des deux colonnes

# je veux revenir en arriere ( retour vers le futur )

mais il est possible est possible en arriere pour voir ce qui avai ete realiser a l'epoque

'''
git checkout 6310025