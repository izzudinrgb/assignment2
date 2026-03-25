Project Title : Elemental Quest

Group Member :
1. Hariz Hakimi Bin Jasri
2. Muhammad Danish Irfan bin Nasimussobah
3. ⁠Muhammad Izzudin bin Bakar
4. ⁠Izzryl Hafizzy bin Azrui Nizam
5. ⁠Luqmanul Hakim bin Ahmad Azizi
6. Mohammad Nazri Aizad bin Mohammad Nazroel
   
Project description :
Elemental Quest features a turn-based combat system where players can attack using elemental based skills, switch element or use potions from their inventory. There are 3 elements which are Fire, Water, and Grass. The logic is simple, Fire can burn Grass, Water can extinguish Fire, while Grass can absorb Water. This is what makes the battle balance. Also, potions provide healing and temporary damage boost. Thus, an inventory system is implemented to manage potions. Besides, a shop system is developed to allows players to purchase additional potions using gold earned from winning battles. After each victory, players receive rewards such as gold or items that can be used to prepare for next battle. 
The goal of this game is to defeat the enemy by reducing their health points (HP) to zero. Before each battle, the player selects an element while the enemy’s element remains hidden until the fight begins. During combat, the player may have the disadvantage if the element selected is weaker against enemy’s element, therefore the player is allowed to switch elements to gain advantage. However, this action consumes one turn. Both the player and the enemy have levels that affect their health and damage output. Hence, making the gameplay increasingly difficult.

System Features
The system is developed using multiple classes,each responsible for specific functionalities in the game. The Character class acts as the base class that defines some attributes such as name, health point, shield and damage. It also includes the attack function, which handles damage dealing and shield blocking mechanics. 
The Player class is inherited from the Character class and introduces additional features such as gold and inventory system. This allows the player to collect, store, and use items throughout the game. 
The Enemy class is also derived from the Character class and represents opponents with customizable health and damage values, allowing different difficulty levels in battles. 
The Menu class manages the main interface of the game, including displaying options such as level selection, shop access, and inventory viewing. It also controls the flow of the game by directing players to different features.
The Shop class implements the purchasing systems, where players can buy potions using gold. It displays available items and processes transactions,updating both the player's gold and inventory. 
The Potion class defines different types of potions such as healing and shield potions. Each potion has its own effect and can be used during battle to enhance the player's survivability. 
The Inventory class manages the collection of potions owned by the player. It allows adding, displaying, and using potions, ensuring proper item management during the game. 
Finally, the Game class serves as the entry point of the program, initializing the game, creating the player, and starting the main menu system.

OOP Concept used:
-Polymorphism
-Encapsulation
-Inheritance
-Abstraction

