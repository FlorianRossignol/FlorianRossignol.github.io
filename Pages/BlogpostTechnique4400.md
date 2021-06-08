## Blogpost Technique Procédural + IA

## Introduction 

Dans le cadre du module GPR440 j'ai dû dévlopper un jeu généré avec un modèle procédural 
en incluant des IA.

## Implémenter la génération Procédural 

Pour la génération procédural je suis parti sur un modèle de Cellular Automata,
histoire de créer une sorte de caverne aléatoire.

## Premier problème et résolution 

Pour la génération Procédural j'avais le code de base mais il fallait savoir comment,dans cette 
caverne générée aléatoirement implémenter ma préfab pour le Player Character ainsi qu'instancier des Colliders et 
Enemis.

## Pour les Colliders 

J'ai du d'abord checker Les Cellules puis si elles sont vivantes alors je ne met pas de Collider 
mais si au contraire elles étaient mortes alors là j'instance les colliders.
Ce qui donne à peu près ça :

![](https://FlorianRossignol.github.io/Images/PhysicsBox.png)

pour un résultat final bien gratifiant :

![](https://FlorianRossignol.github.io/Images/PhysicsBoxFinal.png)

## Le problème du spawn 

Pour le player Character je voulais qu'il spawn random dans mon cellular automata, mais pour ça j'ai du implémenter 2, 3 trucs

de un prendre des régions et des Tiles random

ensuite prendre la position dans le cellular automata 

pour enfin instancier la prefabs du player

et pour finir implémenter de quoi suivre le player avec la caméra 

ce qui nous donne ça :


![](https://FlorianRossignol.github.io/Images/Startingroom.png)

## Pour l'objectif et les enemis

Et bien c'est à peu près simmilaire sauf qu'en plus de l'instancier on doit checker 
que le player ainsi que l'objectif ne sois pas instancié au même endroit

Ce qui donne ceci

Pour l'objectif :

![](https://FlorianRossignol.github.io/Images/SpawnObjectifs.png)

Et enfin les ennemis :

![](https://FlorianRossignol.github.io/Images/SpawnEnemy.png)

## les choix de design 

Pour cette sommative j'ai décidé de me concentrer sur le procédural et l'ia principalement,

ce qui fait que vous ne pouvez pas mourir ! 

et oui les ennemis sont divertissant mais je voulais d'abord montrer ce que je savais faire procéduralement ainsi qu'avec l'ia.


## L'ia 


J'ai 2 types d'ia bien distingue

dune un petit slim tout mimi mais qui cours sur vous dés qu'il vous voit !

et de deux un squelette qui va plus lentement mais qui a beaucoup plus d'animation lors qu'il reçoit un coup.


## Conclusion 

- Et bien c'était pas gagné d'avance car au début je ne comprennait pas trop les algorithmes mais je me suis mis à les aimer
- Car oui ils sont vachement utile les bougrent !
- J'ai pu bien intégrer plusieurs choses et c'était vraiment très intéréssant 
- Vivement le module physique



