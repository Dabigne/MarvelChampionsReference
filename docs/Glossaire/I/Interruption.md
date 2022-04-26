# Interruption
Une capacité d’interruption est un type de capacité déclenchée signalé par l’indicatif de déclenchement `«Interruption»` en gras. Les capacités d’interruption peuvent être exécutées chaque fois que les conditions de déclenchement spécifiées se produisent telles que décrites dans le texte de la capacité d’interruption. La capacité d’interruption interrompt la condition de déclenchement spécifiée et se résout immédiatement avant que cette condition de déclenchement ne se résolve.

- Plusieurs interruptions peuvent être déclenchées par la même condition de déclenchement.
- Une capacité d’interruption est exécutée quand sa condition de déclenchement devient imminente, mais avant qu’elle ne se résolve. Les opportunités d’interrompre ont lieu dans l’ordre des joueurs jusqu’à ce que tous les joueurs aient consécutivement passé. 
- Une fois que tous les joueurs ont consécutivement passé leur opportunité d’interrompre une condition de déclenchement imminente, aucune autre interruption pour cette condition de déclenchement spécifique ne peut être utilisée.
- Si une interruption change (via un effet de remplacement) ou annule une condition de déclenchement imminente, d’autres interruptions à la condition de déclenchement originelle ne peuvent pas être déclenchées. 

**Voir aussi :**  
[[Annuler]]  
[[CapaciteDeclenchee]]  
[[EffetsRemplacement]]