## Blogpost Technique Rollback Multiplayer

## Introduction 

Dans le cadre du modue GPR5100 j'ai du créer un jeu en Multijoueur fonctionnant au Rollback.

## Défi et contrainte 

Lors de ce module, j'ai du beaucoup me concentrer, car je retourne dans le c++ ainsi que sa comprhéension,
et le multijoueur qui était nouveau pour moi.

## Apprendre le Multi ainsi que comment fonctionne un serveur et internet

Pour devoir faire mon jeu j'ai du commencer pars apprendre d'où venait le réseau et particulièrement 
les protocoles utilisé pour communiquer entre un serveur et un client.

## La notion de client et serveur 

Pour commencer il faut savoir comment communique un client avec un serveur
et plus précisément comment ça fonctionne.


## UDP TCP 

pour la comunication entre les deux, on observe 2 choix
l'un convienda mieux à une situation que l'autre 

Pars exemple: le fait d'avoir juste une connexion = TCP

avoir des packets d'inputs = UDP

## La création

A la base je n'avais qu'un shooter en 2 contre 2,
ma philosophie fut de créer un magnifique pong entre 2 joueurs

## Commencer pars remlacer les nom variables etc

Pour ce faire j'ai du en premier temps changer les dossier ainsi que les variables avec les noms approprié 

## Créer une Ball

Pour un pong il faut une boule 

alors j'ai pu créer ma boule dans le BallGameManager

![](https://FlorianRossignol.github.io/Images/BallManager.h.png)

puis un cpp

![](https://FlorianRossignol.github.io/Images/BallManager.cpp.png)

## Load les texture et faire un background

Pour la suite du jeu il me fallais un background je me suis donc collé à la tâche

![](https://FlorianRossignol.github.io/Images/ClientManagerInit.png)

Puis donner tout les composants pour la texture du background

![](https://FlorianRossignol.github.io/Images/ClientManagerInit2.png)

## Spawn le player et la ball

pars la suite il me fallait implémenter le player et la ball 

d'abord dans le client :

![](https://FlorianRossignol.github.io/Images/SpawnBallClient.png)

![](https://FlorianRossignol.github.io/Images/SpawnPlayerClient.png)

puis sur le serveur :

![](https://FlorianRossignol.github.io/Images/SpawnPlayer1.png)

![](https://FlorianRossignol.github.io/Images/SpawnPlayer2.png)

![](https://FlorianRossignol.github.io/Images/SpawnBall1.png)

![](https://FlorianRossignol.github.io/Images/Spawnball2.png)


## Les échecs 

malheureusement je n'ai pas pu implémenter après plus de 4h00 dessus
les points de vies qui mène à la victoire.


## Conclusion 


- Du bon côté 
- Très intéressent la relation client serveur
- Beaucoup mieux comprendre le networking
- Hâte d'appendre encore plus



