# Labo : DnD lite

Le programme simule un combat entre deux adversaires dans un jeu inspiré des règles de Dungeon & Dragons. 

Pour cette question les règles ne sont pas les règles de D&D. N’essayez pas de vous fier à votre connaissance du jeu.

Utiliser au besoin :
- Méthodes
- Tableaux
- Boucles
- Conditions

Le programme :

- Menu initial avec le choix entre

-- Afficher les stats des combatants
-- Simuler un combat complet
-- Afficher un résumé/historique de combat

### Afficher les stats des combatants : 
- Les caractéristiques initiales de chaque combattant (hp, attaque, défense, dé pour le dommage, bonus de dommage)

### Simuler un combat :
- Jsuqu'à ce que l'un des deux combatants soit mort 

--	Calculer et afficher l’initiative avec un message qui donne l’ordre d’attaque

--	Calculer les attaques les dégâts et afficher les résultats

### Afficher un résumé/historique de combat :

-- Un message indiquant le vainqueur

-- l'historique des tours de combat avec : les jets de toucher (le d20), les dégâts de chacun, les points de vie restant

Chaque combattant a 30 points de vie (hp).

Le premier est un guerrier humain se battant avec une épée longue, un bouclier et une cotte de mailles :

-	Statistique d’attaque : nombre aléatoire de 14 à 18 
-	Statistique de défense : 18
-	Dé de dommage : 8

C’est aussi un escrimeur, il faudra toujours ajouter 2 pts aux dommages qu’il cause.

Le second est un orc se battant avec une épée longue, à deux mains :

-	Statistique d’attaque : nombre aléatoire de 10 à 18 
-	Statistique de défense : 14
-	Dé de dommage : 10

Puisqu’il se bat à deux mains, le jet de toucher et les dommages de l’orc sont augmentés de 2.

Calcul du bonus de dommages

Selon la statistique d’attaque chaque combattant a un **bonus de plus** appliqué à ses dommages. Pour calculer ce bonus :

(Statistique d’attaque – 9) / 2
 
Déroulement du combat

- Initiative : 

-- 1 dé à 20 faces (nombre aléatoire de 1 à 20) est lancé par chaque protagoniste, celui qui a le plus haut lancé attaque en premier. 

-- En cas d’égalité l’humain attaque en premier parce que c’est le héros!

- Toucher et dommages :

-- Chaque attaque nécessite le lancer du dé à 20 faces (nombre aléatoire de 1 à 20), c'est le jet de toucher

-- Si le résultat du jet de toucher est plus grand ou égal à la statistique de défense on applique les dommages aux points de vie de l’adversaire.

-- Les dommages correspondent au lancé du dé de dommage, un nombre aléatoire de 1 à la valeur du dé de dommage (ex : humain 1 à 8).

-- On ajoute aux dommages les bonus de dommage




