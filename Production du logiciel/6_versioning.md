### Points importantés liés à : 'Production du logiciel', dans la partie 'versioning'

- La notion de "bonne version" d'un logiciel permet de prendre en compte des différentes options et systèmes.
- La gestion des versions d'un seul fichier source est relativement simple comparée à la gestion de la configuration du logiciel.
- Git est un outil de gestion de configuration pour stoquer les archives d'un ensemble de fichiers appelé projet.
 Quand git init est exécuté, un dossier .git est créé avec un dépôt pour stocker les versions des fichiers. 
- Les commandes git add et git commit permettent de planifier et d'archiver respectivement des fichiers dans un dépôt local.
- La commande git log permet d'afficher l'historique des archivages.
 La commande git checkout permet d'extraire d'une archive désignée par son code de hachage SHA-1. 
- Il est possible d'attribuer un nom symbolique à une archive à l'aide d'une étiquette à l'aide de la commande git tag.
- La commande git status permet de voir quels fichiers ont été modifiés et sont en train d'être indexés dans la zone de transit.
 La commande git reset permet de supprimer un fichier de la zone de transit.
- La commande git diff permet de comparer la version de l'espace de travail avec la version en transit si elle existe, et sinon avec le dépôt.
- La commande git checkout -b permet de créer une nouvelle branche et de basculer dessus tandis que la commande git branch -d est utilisée pour supprimer une branche.
 La commande git peut être utilisée pour créer un dépôt "distant" et ajouter ce dépôt à un espace local.
- Les commandes git push et git clone peuvent être utilisées pour pousser un dépôt local vers un dépôt distant ou pour cloner un dépôt distant.
- Git status indique l'état de la branche courante par rapport à sa branche amont et si les archives supplémentaires dans la branche master du serveur distant doivent être poussées.
 La commande git fetch récupère la branche master du dépôt origin dans la branche amont origin/master 
- Les commandes git fetch et git merge FETCH_HEAD peuvent être remplacées par l'unique commande git pull 
- Un conflit peut apparaitre lorsque 2 développeurs ont archivé des modifications d'un même fichier dans leurs dépôts locaux respectifs
 Après une tentative de push (envoi des modifications locals au dépôt distant), un message d'erreur apparait si le dépôt distant contient des travaux que l'on n'a pas localement. 
- Le git pull se décompose alors en git fetch pour rapatrier les changements distants puis fusionner les deux branches avec git merge.
- La fusion automatique peut échouer alors on obtient un message de conflit et un fichier préparé pour la résolution du conflit, le résultat doit être confirmé avant de pouvoir commit avec git commit -a.
 La commande git pull a réalisé le git fetch et le git merge FETCH_HEAD.
- La référence FETCH_HEAD indique le résultat du dernier git fetch. 
- La référence ORIG_HEAD indique l'ancienne position de HEAD sur la branche master.
