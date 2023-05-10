# Projet dev_mobile
 
Guide pour contribuer

Ce projet est ouvert aux contributions de la communauté, et nous sommes ravis de recevoir vos suggestions, corrections et améliorations. Si vous n'êtes pas familier avec l'utilisation de GitHub, voici un guide rapide pour vous aider à commencer.
Étapes préliminaires

    Créez un compte GitHub : Si vous n'en possédez pas déjà un, rendez-vous sur https://github.com et créez un compte.

    Installez Git : Git est un système de contrôle de version largement utilisé. Vous pouvez le télécharger et l'installer à partir de https://git-scm.com/downloads en fonction de votre système d'exploitation.

Fork et clone du dépôt

    Fork du dépôt : En haut de cette page, cliquez sur le bouton "Fork" pour créer une copie du projet sur votre propre compte GitHub.

    Clone du dépôt : Sur votre dépôt nouvellement forké, cliquez sur le bouton "Code" et copiez le lien URL fourni. Ouvrez ensuite votre terminal, naviguez vers le répertoire souhaité et exécutez la commande suivante pour cloner le dépôt en local :

    bash

    git clone <URL_DU_DÉPÔT>

Effectuer des modifications et les soumettre

    Créez une branche : Avant de commencer à apporter des modifications, créez une nouvelle branche pour travailler dessus. Utilisez la commande suivante pour créer une branche avec un nom descriptif :

    css

git checkout -b <nom_de_la_branche>

Effectuez vos modifications : Faites vos modifications, ajoutez de nouveaux fichiers, supprimez ce qui n'est plus nécessaire, etc. Vous pouvez utiliser votre éditeur de code préféré pour cela.

Validez vos modifications : Utilisez la commande git status pour vérifier les fichiers modifiés. Ensuite, utilisez la commande git add pour préparer les fichiers modifiés pour le commit :

csharp

git add <nom_du_fichier_modifié>

ou

csharp

git add .

pour ajouter tous les fichiers modifiés.

Effectuez un commit : Utilisez la commande git commit pour créer un commit avec un message descriptif concernant vos modifications :

sql

git commit -m "Description des modifications"

Push vers votre dépôt : Utilisez la commande git push pour envoyer vos modifications vers votre dépôt GitHub :

perl

git push origin <nom_de_la_branche>

Créez une pull request : Sur la page de votre dépôt GitHub, vous devriez voir un bouton "Compare & pull request". Cliquez dessus, vérifiez que les modifications sont correctes, puis soumettez la pull request. Nous examinerons vos modifications et les fusionnerons si elles sont conformes aux normes du projet.
