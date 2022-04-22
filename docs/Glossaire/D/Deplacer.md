# Déplacer
Certaines capacités permettent aux joueurs de déplacer des éléments de jeu comme des cartes, des dégâts ou des menaces.
- Quand un élément se déplace, il ne peut pas se déplacer vers l’emplacement où il se trouve déjà (son emplacement actuel).
- S’il n’y a pas de point de départ ou de destination valide pour un déplacement, ce déplacement ne peut être effectué.
- Il est possible pour les dégâts d’être déplacés d’un compteur vers une carte (et vice versa).
- Si des dégâts sont déplacés d’un compteur vers une carte, augmentez le nombre de points de vie sur le compteur du montant indiqué (sans dépasser les points de vie maximums de la carte associée) et placez une quantité équivalente de dégâts sur la carte.
- Si des dégâts sont déplacés d’une carte vers un compteur, retirez les dégâts de la carte et diminuez le nombre de points de vie sur le compteur d’un montant équivalent.
- Si des dégâts sont déplacés vers un personnage, on considère que les dégâts déplacés sont infligés à ce personnage.
- Si des menaces sont déplacées vers une manigance, on considère que les menaces déplacées sont placées sur cette manigance.