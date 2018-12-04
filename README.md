# MMorpion
Multi morpion

En bref :
	Le morpion est ce jeu simple où on dessine une grille de 3 par 3, se joue à 2. chaque joueur joue l'un après l'autre en dessinant un croix ou un rond dans les case jusqu'à réussir à aligné 3 de ses marques avec interdiction de jouer dans une case déjç utilisé.
	Le Multi Morpion, en simple, c'est des morpions dans un morpion. Un premier morpion est dessiné, et d'autre morpion sont dessiné dans chaque case du premier morpion. chaque nouvelle série de morpion ajouté dans les plus petit morpion déjà dessiné est une puissance de multi morpion supplémentaire, sachant que le morpion classique est celui de puissance 1.
	Les joueur joue dans les plus petit morpion dessiné et gagne les case des morpion suppérieur en gagnant les morpion plus petit.
	Lorsqu'un joueur joue dans une case, cela indique le petit morpion dans lequel le joueur suivant doit jouer.
	Celà implique une possibilité de tactique divers selon la puissance du Multi Morpion et le nombrede joueurs.

Règle du multi-morpion :
	1 - Les joueurs choisisse une puissance du morpion de 1 à l'infinie (sachant que l'ordre de grandeur du temps d'une partie est de quelque seconde en puissance 1, quelque minutes en puissance 2, quelques heur en puissance 3, quelque jour en puissance 4 et ainsi de suite)
	2 - Pas plus de puissance +1 joueurs sur une même partie
	3 - Les joueurs décide d'un ordre de tour (qui joue en premier, qui suis, etc...) et de la marque propre à chaque joueur
	3 - Le premier joueur joue dans le morpion de puissance n de sont choix (n étant la puissance du multi morpion, la puissance d'un morpion précit au multi morpion est le nombre d'ittération de petit morpion pour l'atteindre. le morpion de puissance n est donc le plus petit morpion)
	4 - Les coordonnées du coup dans le morpion de puissance n indique les coordonnées du morpion de puissance n dans le morpion de puissance n-1 dans lequel le joueur suivant doit jouer. Si ce joueur est dans l'impossibilité d'y jouer (toutes les case sont occupé) il peut jouer dans n'importe quel case du morpion de puissance suppérieur.
	5 - Le premier cas de 3 marques d'un même joueur aligné dans un morpion donne ce morpion au joueur correspondant et donne la case correpondante dans le morpion de puissance inférieur. si le morpion gagné est le morpion de puissance 1, le joueur correspondance gagne la partie.