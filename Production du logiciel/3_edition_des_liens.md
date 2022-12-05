### Points importantés liés à : 'Production du logiciel', dans la partie 'edition des liens'

- L'éditeur de liens est responsable de résoudre les références externes des fichiers objets, en faisant correspondre les références publiques et externes.
- Les erreurs les plus courantes rapportées par un éditeur de liens sont "référence externe non résolue" et "référence publique doublement définie". 
- Sous Linux, l'utilisation de l'diteur de liens ld implique l'utilisation de chemins non portables.
 L'édition de liens permet de lier des fichiers objets et des bibliothèques afin de créer un fichier exécutable plus petit.
- Il existe différents logiciels pour éditer des liens de manière dynamique ou statique, ainsi que des bibliothécaires pour créer des bibliothèques à partir de fichiers objets.
- Les bibliothèques peuvent contenir des ressources Windows ou des classes Java compilées, et sont disponibles sous les extensions .dll, .so ou .jar.
 La recherche de fr/telecomlille/utils/Hello.class doit se faire à partir du dossier bin ou du fichier lib/mylib.jar.
- La variable d'environnement CLASSPATH spécifie une liste de dossiers et de fichiers qui peuvent contenir des classes compilées.
- La commande java permet de spécifier un chemin d'accès pour la recherche de fr/telecomlille/utils/Hello.class.
