# README.md

## Travaux Pratiques - Tests Unitaires avec JUnit

Ce projet a été réalisé dans le cadre du cours de Génie Logiciel Avancé du Master 1 à l'Ecole National d'Informatique, Fianarantsoa pour l'année 2024. Les travaux pratiques portent sur l'implémentation de tests unitaires avec JUnit, en mettant en pratique l'alternance codage/test.

### Objectif du TP

L'objectif principal est de développer un programme pour résoudre le problème de la représentation arithmétique avec plusieurs devises. L'approche consiste à créer des tests unitaires avec JUnit pour garantir le bon fonctionnement du programme tout au long du processus de développement.

### Contenu du Projet

Le projet se divise en plusieurs parties, chacune abordant une étape spécifique du développement :

1. **Classe Money**: Définition d'une classe pour représenter une valeur monétaire pour une devise donnée. Les opérations arithmétiques simples sont implémentées, notamment l'addition entre deux valeurs de même devise.

2. **Tests Unitaires avec JUnit**: Les tests unitaires sont écrits pour la classe Money en suivant le processus "coder ; tester ; coder ; tester" afin de garantir le bon fonctionnement des méthodes.

3. **Classe MoneyBag**: Introduction d'une classe permettant de gérer des valeurs monétaires de différentes devises. Les opérations d'addition entre Money et MoneyBag sont implémentées pour prendre en charge des devises multiples.

4. **Intégration des Classes Money et MoneyBag**: Les classes Money et MoneyBag sont intégrées pour gérer toutes les combinaisons possibles d'opérations arithmétiques entre elles.

5. **Simplification**: Les tests et les classes sont adaptés pour garantir une simplification appropriée des MoneyBag en Money lorsque cela est nécessaire.

### Comment Utiliser ce Projet

1. Cloner le dépôt sur votre machine locale.
2. Importer le projet dans votre environnement de développement (par exemple, Eclipse).
3. Exécuter les tests unitaires inclus pour vérifier le bon fonctionnement des classes Money et MoneyBag.
4. Modifier et étendre le code selon les besoins du projet tout en veillant à maintenir la couverture de tests.

Pour plus d'informations sur JUnit, veuillez consulter la documentation officielle [ici](http://junit.sourceforge.net/).

---
*Ce projet a été réalisé dans le cadre d'un cours à l'ENI et est disponible sous licence [MIT](LICENSE).*
