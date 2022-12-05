### Points importantés liés à : 'Production du logiciel', dans la partie 'programmation modulaire'

- La structuration d'une application en langage C se fait à l'aide de modules de compilation séparée, chacun ayant sa logique et ses fonctions.
- Les variables d'un module doivent être accessibles uniquement via les fonctions pour assurer sa cohérence et le principe d'encapsulation. 
- Le fichier d'en-tête d'un module ne doit comporter que des prototypes, des types et des constantes, et est protégé contre les inclusions multiples.
 La documentation et l'utilisation des fonctions static dans le code source contrôlent l'encapsulation.
- Les variables globales doivent normalement être static dans le fichier source.
- Une préfiguration de la notion d'instance existe dans le langage C, pour rendre le module d'usage général capable de gérer plusieurs compteurs.
 On peut séparer les modules de test et les modules applicatifs afin qu'ils ne soient pas vus l'un par l'autre.
- Le Makefile et l'environnement de développement intégré peuvent produire un exécutable de test et un exécutable applicatif séparément.
- Les modules de test ne doivent pas inclure de fonctions de test ou de fonctions d'assertion de tests, les fonctions d'assertion étant réservées au main de test.
 Il existe une fonction CuSuiteAddSuite qui peut regrouper plusieurs suites de test en une seule. 
- Tous les modules applicatifs ont leur propre module de test.
- Le main de test combine tous les modules de test en une seule suite qui permet de tester tous les modules applicatifs.
