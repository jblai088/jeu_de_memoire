# Jeu de mémoire

Mon site web est un jeu de mémoire. Le jeu a la forme d'une grille dans laquelle chaque case contient une image, normalement masquée. Chaque image utilisée existe en exactement deux exemplaires dans la grille. Le but est de découvrir toutes les paires d'images. 

## Forme de base du jeu
Au début du jeu, toutes les images sont placées aléatoirement dans la grille et masquées.

Cliquer sur une case révèle l'image qu'elle contient. Si cette image est identique à celle  révélée au clic précédent, alors ces deux images demeurent visibles jusqu'à la fin du jeu; sinon, l'image précédente redevient masquée. Le jeu prend fin quand toutes le images sont découvertes.

On comprend que se souvenir des positions, mêmes approximatives, d'images vues et redevenues masquées assure une résolution rapide. 

Le jeu compte le nombre de clics et enregistre les meilleurs pointages, c'est-à-dire les plus petits nombres de clics pour terminer le jeu.


## Technologies
J'utilise bien entendu HTML pour structurer ma page, et CSS pour y positionner les éléments. Pour la logique servant à interagir avec l'utilisateur, j'utiliserai JavaScript. 