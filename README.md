# La liste des participants à la séance git

git init ->> Seulement une fois, pour initialiser un nouveau repository (dossier où le contenu sera tracké dans git)

git status ->> voir l'état, ce qui a été modifié, pas tracké ou prêt à être mis dans un commit

(pour rappel, un commit = une "copie" de votre dossier à un instant t, dont on pourra revenir  si jamais on a un soucis)

git add [nom fichier ou . ou -A] tracker ou ajouter le fichier à l'instant t dans le futur commit

git commit -m "le message" sauvegarder les fichiers ajoutés depuis la commande "git add" dans un nouveau commit avec le message spécifié

---> Risque de devoir configurer nom et adresse mail

git diff -> voir les modifs du dossier courant depuis l'ancien commit (local)

`git clone ` --> Pour télécharger un repository git distant avec son historique et tout de configuré

`git push` --> Pour envoyer vos commits locaux dans le cloud

`git pull` --> Pour récupérer les commits distants

`git checkout -b [nom de la branche]` pour créer une branche.

### TP

1. Configurez git sur votre ordinateur.
2. Fork ce repository (sur github)
3. Télécharez le repo nouvellement forké avec `git clone`
4. Créer un fichier portant votre pseudo et ayant en contenu votre pseudo aussi (avec votre ordi)
5. Enregistrer tout ça dans un commit `git add` puis `git commit`
6. Envoyer ses changements avec la commande `git push`
7. Créez une Pull Request (sur github)
