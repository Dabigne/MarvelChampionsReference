# Modificateurs
Le jeu vérifie constamment et actualise (si nécessaire) le compte de toutes les variables qui sont modifiées.  
Chaque fois qu’un nouveau modificateur est appliqué ou retiré, la valeur concernée est recalculée entièrement depuis le début en prenant en compte la valeur de base non modifiée et tous les modificateurs actifs. 

- Le calcul d’une valeur considère tous les modificateurs comme étant appliqués simultanément. Cependant, lors du calcul, tous les modificateurs additifs ou soustractifs sont calculés avant les modificateurs multiplicatifs ou divisifs. 
- Si une valeur est «fixée» à un nombre spécifique, le modificateur fixé supplante tous les autres modificateurs. Si plusieurs modificateurs fixant une valeur entrent en conflit, le modificateur le plus récent supplante les autres. 
- Après que tous les modificateurs actifs ont été pris en compte, si une valeur est inférieure à zéro, elle est considérée comme étant égale à zéro. Une carte ne peut pas avoir de valeur «négative» d’icônes, d’attributs, de traits, de coût ou de mot-clé.
- Toutes les fractions sont arrondies au nombre supérieur après application de tous les modificateurs. 

**Voir aussi :**  
[[ValeurBase]]  
[[Imprime]]