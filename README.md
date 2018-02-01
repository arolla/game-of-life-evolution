# Game-of-life-evolution

Le jeux de la vie est un automate cellulaire, et non un vrai jeux.
Il est régie par des règles de naissance/survie/mort de cellules sur une grille.

# Régles du Game Of Life

Régle n°1: Si une cellule a exactement trois voisines vivantes, elle est vivante à l’étape suivante.
C’est le cas de la cellule verte dans la configuration de gauche.

Régle n°2: Si une cellule a exactement deux voisines vivantes, elle reste dans son état actuel à l’étape suivante.
Dans le cas de la configuration de gauche, la cellule située entre les deux cellules vivantes reste morte à l’étape suivante.

Régle n°3: Si une cellule a strictement moins de deux ou strictement plus de trois voisines vivantes, elle est morte à l’étape suivante. 


_Descriptif complet ici: https://fr.wikipedia.org/wiki/Jeu_de_la_vie _ 

# Consigne & conseils

- Implémentez les règles du GoL en TDD, en privilégiant les baby-steps

tips: La ganularité de la baby step se situe "en dessous" de celle de la règle sur une grille
tips: D'autres règles arriveront, pensez à avoir un code soupple et évolutif

