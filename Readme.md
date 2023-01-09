# EXERCICE n°2 :

Vous allez créer un nouveau projet sur votre dépot git.
Vous allez appeler votre projet “exercice2”.

***solution :***
>*Se rendre sur [Github](https://github.com) ou [Gitlab](https://about.gitlab.com/) est creer un nouveau repository (public) avec le nom exercice2*

##Ci-dessous les étapes à effectuer :

● En local, vous allez un projet exercice2, vous allez ensuite récupérer un projet présent sur git.
● Il vous faudra utiliser la commande “git clone”.
● Le lien du dépot à cloner est : https://gitlab.com/mohamed.formation.m2I/m2iformation_exo.git
***solution :***
>Ce placer dans son dossier de travail puis cloner le dépot grace a son lien :
```
git clone https://gitlab.com/mohamed.formation.m2I/m2iformation_exo.git
cd m2iformation_exo
```


● Il s’agit d’un site web pour publier votre CV.
● Il faudra modifier le fichier html pour faire apparaître vos informations personnels sur le CV.

***solution :***
>Effectuer des modifications sur les fichiers récuperé (changement des informations et personalisation du style) puis les commit sur le dépot local
> Deuxiéme étape ajouter ces fichier à notre dépot local et le commit :
```
git add .
git commit -m "modifications du fichier HTML".
```


● Une fois que vous avez modifié ce CV, il faudra effectuer les opérations nécessaire pour pousser sur votre dépôt distant (exercice2) la version modifié du site.

***solution :***
>Changer l'adresse du remote distant (dans le répertoire cloné) :
>On regarde l'adresse du remote actuelle :
```
git remote -v
```
>Que l'on supprime :
```
git remote rm origin
```
>On remplace par notre dépot distant crée au debut de l'exercice:
```
git remote add origin https://github.com/nom_utilisateur_github/exercice2.git
git branch -M main
git push -u origin main
```

***solution BONUS :***
>Puisqu'il s'agit d'un site web statique github nous offre la possibilllité de publier ce site :
> onglet Settings de notre repository 
> Choisir Pages
> Selectionner la branch main puis save
> Le site sera disponible aprés quelques secondes.
