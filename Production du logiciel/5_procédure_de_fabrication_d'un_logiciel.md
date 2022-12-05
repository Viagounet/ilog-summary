### Points importantés liés à : 'Production du logiciel', dans la partie 'procédure de fabrication d'un logiciel'

- L'outil make permet d'automatiser tâches peu encombrantes comme la compilation séparée et l'édition de liens.
- Il est basé sur des relations de dépendance entre les fichiers décrites dans un fichier Makefile. 
- Il interprète récursivement les règles de production définies dans le Makefile afin d'obtenir un exécutable à jour.
 La syntaxe générale d'une règle de production est la suivante : cible : dépendances (ou prérequis);
- Les cibles phony (comme "clean" ou "all") n'ont pas pour objectif de produire un fichier; 
- Make cherche à produire les dépendances récursivement et compare les dates des cibles et dépendances pour déterminer si la cible est à jour. Si tel n'est pas le cas, les commandes associées sont lancées.
 Il est important de répartir les fichiers de développement à l'aide de répertoires différents. 
- Les variables permettent de définir des chemins d'accès, des fichiers, des extensions des outils, les options des outils, etc. 
- On peut affecter une valeur à une variable avec le signe "=" ou ": =", et référence à une variable en utilisant le signe dollar ($). De plus, il existe des variables automatiques et des variables pour lancer des commandes.
 Make utilise des variables, prédéfinies ou non, pour lancer certains outils.
- On peut factoriser des dépendances en mettant plusieurs fichiers à gauche du caractère « : » d’une règle.
- Des fonctions telles que foreach et subst permettent de modifier des variables.
 ANT est un utilitaire similaire à make mais qui permet de générer des applications Java avec des performances plus rapides.
- Le fichier antfile est écrit sous une syntaxe XML et peut être lancé en ligne de commande ou depuis un environnement de développement.
- Le fichier antfile contient des cibles qui contiennent des tâches, telles que des opérations de compilation ou d'archives, et peuvent être modifiées en fonction des besoins.
 Un projet Ant est spécifié à l'aide d'un fichier build.xml et il comprend des cibles et des tâches.
- Les propriétés sont une alternative aux variables de make et ne peuvent pas être modifiées une fois définies.
- Il existe des propriétés système ainsi que des propriétés ant prédéfinies telles que basedir, ant.file, ant.version et ant.project.name.
 Les IDEs (Integrated Development Environment) facilitent le développement des logiciels en offrant de la convivialité et en cachant la chaîne de développement à l'utilisateur.
- Les projets correspondant aux fichiers makefiles permettent de produire un exécutable ou une bibliothèque.
- Des boîtes de dialogue permettent d’ajouter ou retirer du projet des fichiers sources, des fichiers objets ou des bibliothèques, et l'environnement bâti ou modifie un makefile en rajoutant des règles de production lorsque l’utilisateur demande la compilation d’un fichier.
