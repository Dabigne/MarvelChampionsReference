# Attaque (activation des ennemis)
Une attaque est un type d’activation des ennemis. Lorsqu’un ennemi attaque, il cible un joueur spécifique. Ensuite, il résout cette attaque contre ce joueur. Pour résoudre une attaque ennemie, respectez les étapes suivantes :  

1. Si un méchant ou un sbire ayant le mot clé `Vilenie` attaque, donnez-lui une carte de boost face cachée prise sur le deck Rencontre. (Si un sbire sans le mot clé `Vilenie` attaque, ignorez cette étape.)
2. Si un joueur souhaite défendre, il incline un héros ou un allié en tant que défenseur. Si un joueur autre que le joueur ciblé défend, le joueur qui défend devient le nouveau joueur ciblé par cette attaque.
3. Retournez chaque carte de boost de l’ennemi attaquant face visible, une à la fois. (Si un sbire sans le mot clé Vilenie attaque, ignorez cette étape.) Puis dans cet ordre :  

	- Résolvez toute capacité «Boost :», indiquée par une icône d’étoile dans le champ de boost.
	- Augmentez de 1 la valeur d’`ATQ` de l’ennemi attaquant pour chaque icône de boost sur la carte.
	- Défaussez chaque carte de boost après sa résolution.
4. Infligez les dégâts de l’attaque. Ces derniers sont égaux à la valeur d’ATQ de l’ennemi attaquant modifiée de la manière suivante :  

	- Si un héros effectue une défense de base contre l’attaque, la quantité de dégâts infligés est réduite par la valeur de `DEF` de ce héros et les dégâts restants sont infligés à ce héros.
	- Si un allié défend contre l’attaque, tous les dégâts de l’attaque sont infligés à cet allié. (Si l’allié est vaincu par l’attaque, les dégâts en excès ne sont pas infligés à l’identité.)
	- Si aucun personnage ne défend contre l’attaque, l’attaque est considérée comme non défendue. Tous les dégâts de cette attaque sont infligés à l’identité du joueur ciblé (même si cette identité est sous sa forme d’alter ego).

**Voir aussi :**  
[[Activation]]  
[[Allie|Allié]]  
[[Boost]]  
[[Cible]]  
[[Defendre|Défense, défendre]]  
[[Degats|Dégâts]]  
[[Ennemi]]  
[[Identite|Identité]]  
[[Mechant|Méchant, deck méchant]]  
[[Sbire]]  
[[Vilenie]]