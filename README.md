# teamswap
Jeu en 3D par équipe dans lequel un membre de l'équipe A tué par l'équipe B se retrouve membre de l'équipe B

Inspirations:
* upgun (pour les déplacements)
* mod minecraft TeamSwappers (pour les règles du jeu): 
https://m.youtube.com/watch?v=JCxJII9xos8&pp=ygUTZ3VpbGwgdGVhbSBzd2FwcGVycw%3D%3D

Jeu à la 3eme personne, vue d'épaule (ou 1ere personne)
Jeu en réseau par équipes

Au début du jeu, les équipes de 4 sont réparties sur la map
Les armes sont:
* couteau pour le corps-à-corps (2-shot)
* pistolet pour le combat à distance (5-shot), 10 balles rechargeables infiniment, cadence de tir déterminée par le jeu, la recharge dure 3 secondes
Chaque joueur reçoit 100 PV et 2 vies supplémentaires (de 100 PV), et les 2 armes

A chaque kill:
* le tueur reçoit, au choix, une vie en + ou une régen complète (le choix se fait au moment du kill, en 5 secondes, si pas dde choix: une vie)
* le tué perd une vie
* le tué va dans la team du tueur (sauf s'il n'a plus de vie, dans ce acs il est éliminé)

Pas de body block

Anti-cheat:
* pas de téléportation
* vitesse max (en tenant compte de la physique)

Déplacement sans contraintes, légère baisse de la gravité pendant les sauts
Vitesse de course rapide (à calbrer)

Communication pendant le jeu:

3 modes à choisir dans les paramètres:
* permanent (dès que le joueur parle, la chat est activé)
* pusk2talk: sur appui d'une touche. Arrêt quand on relâche la touche
* rien (pas de chat)

Chaque joueur possède un tab ou on peut voir tous les joueurs, rassemblés par équipe (en colonnes)
Le tab est accessible par une touche, chaque joueur possède un checkmark pour les appels vocaux.
Le joueur coche les personnes avec qui il parle dans le mode "personne sélectionnée dans le tab"

3 modes à choisir dans le jeu (par raccourci clavier):
* public
* team
* personne sélectionnée dans le tab

Contrainte supplémentaire:
* chat vocal de proximité (seules les personnes présentes dans la zone définie par le jeu autour du joueur peuvent communiquer)

