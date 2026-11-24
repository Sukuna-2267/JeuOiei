# JeuOie

Jeu de l'oie personnalisable, réalisé avec l'aide d'une IA générative (TP8 - Vibe coding).

## Lancer le jeu

Ouvrir le fichier `jeu_de_l_oie.html` dans un navigateur (aucune installation nécessaire).

## Fonctionnalités

- Saisie du nombre d'équipes (de 2 à 10) et bouton pour lancer le jeu
- Plateau de 63 cases avec la position et les déplacements des pions
- Règles classiques : oies, pont, auberge, puits, labyrinthe, tête de mort
- Arrivée exacte sur la case 63 (sinon rebond)
- Cartes action, gagnées sur certaines cases et jouées avant de lancer le dé
- Cases Chance qui tirent une action au hasard
- Zone « API Actions » pour ajouter de nouvelles actions

## Conditions techniques

- Un seul fichier HTML / CSS / JavaScript
- Exécution en local dans un navigateur, tous systèmes d'exploitation

## Aspect graphique

Ambiance jardin : fond vert, cases colorées selon le type d'action, pions numérotés par équipe.

## Mon action ajoutée : Tempête

Tous les autres joueurs reculent de 2 cases. Elle peut apparaître sur une case du plateau, en carte Chance ou en carte action.

## Tests effectués

- Parties de 2, 5 et 10 équipes
- Plusieurs parties de suite
- Utilisation des cartes action
- Fin de partie à la case 63

## Limites et regard critique

Le code a été généré avec une IA, puis vérifié et testé par mes soins. Il faut relire et tester chaque modification demandée à l'IA, car elle peut casser des fonctions existantes.
