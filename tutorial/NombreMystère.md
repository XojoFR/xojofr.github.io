[Accueil](https://xojofr.github.io)

# Le nombre mystère

* TOC
{:toc}

## Principe du jeu

Le principe de ce jeu est relativement simple : trouver un nombre mystère dans un interval défini ; a chaque tentative de l'utilisateur on répond par c'est plus grand, c'est plus petit ou c'est gagné. Le principe pour gagner au plus vite est de proposer le nombre situé entre la valeur la plus petite et la valeur la plus grande. Certains nombres sont donc plus facile que d'autres à trouver. Par exemple dans l'inteval 0 à 100 le nombre de coup pour trouver la solution est de 1. Nous nous servirons de la difficulté pour déterminer le nombre de points gagné lors de la résolution du problème. Si l'utilisateur mémorise bien les valeurs minimale et maximale et trouve la solution en un nombre de tentative égale au nombre de tentatives logiquement nécessaires il gagne un nombre de points égal à l'interval entre les valeurs à trouver. S'il est chanceux et fait mieux il gagne un nombre de points égal à l'interval entre les valeurs à trouver plus un bonus de points égal à 10% de l'interval par tentative économisée. S'il fait moins bien que la solution logique il gagne un nombre de points égal à l'interval entre les valeurs à trouver moins un bonus de points égal à 5% de l'interval par tentative économisée.

Pour cette exercice nous allons nous efforcer de resoecter des règles de programmation :

* Pas de duplication de code. Nous allons par exemple utiliser le même code pour la logique de notre jeux dabns les différentes version de notre application
* Pas de nombre magique. Nous utiliserons au maximum des constantes à la place des nombres fixé dans le code. Par exemple pour l'interval dans lequel se situe le nombre mystère nous utliserons minInterval et maxInterval à la place de 0 et 100. Ce qui permettra de maintenir facilement notre code.
* Internationalisation des chaines de caractère. Afin de prévoir le succès internationnal de notre applcation nous utiliserons des chaines de caractères localisé.
* Internationalisation du code : Pour que notre code soit échangeable avec d'autres développeur nous utiliserons l'anglais pour nos noms de variables, methodes,etc.

Nous allons créer une version Desktop (macOS, Windows, Linux), une version mobile (iOS) et une version Web avec Xojo. 

## Code du jeu
## Interface du jeu
### Interface Desktop
### Interface Mobile
### Interface Web
## Solutions complètes
### Desktop
### Mobile
### Web
