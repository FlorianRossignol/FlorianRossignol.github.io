## Blogpost Technique, Création d'un moteur physique

## Introduction 

Pour la fin de ma première année de formation je devais rendre en fin d'année, un moteur physique fonctionnel.

## Défi et Contrainte 

Pour le moteur physique j'avais plusieurs défis à régler.

## 1 / pouvoir ratrapper mes lacunes en math et physique

Contrairement à certains je partais avec aucune notion de physique et peu de bagage en Math,
car suite à mon parcours je n'ai jamais vu de physique de ma vie.

J'ai du apprendre beaucoups de choses pendant le module //en plus de me remettre au c++
j'ai mis des moyens à l'aide d'amis pour de l'aide dans les deux branches et ai pu réussir à mieux comprendre le tout

## 2 / pouvoir tout implémenter 

Bien que les cours de ce troisième module étaient très intéressant, le manque de communication part rapport 
au rendu final étaient très flou voir inexistant, donc j'ai du redoubler d'effort et m'organiser correctement 
pour rendre un moteur phyique dans les temps.

## La construction du moteur physique 

Le moteur physique a du être dévlopper en plusieurs semaines.
On avait les cours purement mathématique et physique le matin pour enchaîner de suite avec l'implémentation.

J'ai absolument adoré le fonctionnement des cours, en effet le faite de voir le théorie puis d'utiliser la théorie
en pratique juste après était tout simplement très intéréssent.
Car en effet de voir ce qu'on vient d'apprendre directement juste après avoir eu la théorie, c'est, selon moi 
le meilleur moyens d'apprendre.

## création des collisions :

Pour le moteur physique j'ai du de base implémenter les différentes classes d'ont j'allait avoir besoin

## 1 Rigidbody 
![](https://FlorianRossignol.github.io/Images/moteurphysique/Rigidbody.h.png)


![](https://FlorianRossignol.github.io/Images/moteurphysique/rigidbody1.cpp.png)


![](https://FlorianRossignol.github.io/Images/moteurphysique/rigidbody2.cpp.png)

## 2 Classe pour les cercles 

![](https://FlorianRossignol.github.io/Images/moteurphysique/Cercle1.h.png)

![](https://FlorianRossignol.github.io/Images/moteurphysique/Cercle2.h.png)

## 3 Classe pour les polygones

![](https://FlorianRossignol.github.io/Images/moteurphysique/Polygone.h.png)


## différentes classes pour les calcules physiques et mathématique

![](https://FlorianRossignol.github.io/Images/moteurphysique/Mrua.png)


![](https://FlorianRossignol.github.io/Images/moteurphysique/Vector2.png)


![](https://FlorianRossignol.github.io/Images/moteurphysique/matrix.png)

## implémentation des collisions entre cercles

![](https://FlorianRossignol.github.io/Images/moteurphysique/Collisioncercle.png)

## 1 Création de la classe et Implémentation des différentes fonction 

j'ai du créer différentes fonctions pour donner de la physique ainsi que des collision pour mes cercles.

On commence pars créer une fonction de cercle :

![](https://FlorianRossignol.github.io/Images/moteurphysique/createcircle.png)

puis ensuite plusieurs fonctions pour simuler et inclure mon cercle dans l'espace :

![](https://FlorianRossignol.github.io/Images/moteurphysique/Collisioncercle.png)

Pour le final on implémente tout ça correctement dans un cpp à pars :


![](https://FlorianRossignol.github.io/Images/moteurphysique/cercleimplem.png)

## 1 Créer une classe qui utilise sfml pour l'affichage graphique 



## 2 Créer le cercle avec les différentes fonctions précédemment crééer

![](https://FlorianRossignol.github.io/Images/moteurphysique/sfmlcircle.png)

## 3 Et voici le rendu de l'affichage

![](https://FlorianRossignol.github.io/Images/moteurphysique/ezgif.com-gif-maker.gif)

## Difficultée rencontrée

Après mon cercle j'ai voulu implémenter des polygones ainsi que des collision entre eux.
Malheureusement après énormément d'éffort je n'ai pas réussi à l'implémenter

## Conclusion 

- J'ai beaucoup aimé faire le moteur physique en c++
- Beaucoup aimé apprendre presque depuis le début
- Décu de pas avoir pu implémenter mes polygones
- Mais je sais à la fin du module qu'être programmeur engine n'est pas fait pour moi 
