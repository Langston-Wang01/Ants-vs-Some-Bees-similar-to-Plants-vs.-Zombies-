# Ants-vs-Some-Bees-similar-to-Plants-vs.-Zombies-
Ants vs Some Bees is a tower defense game (similar to Plants vs. Zombies, where you must populate your colony with a variety of 'special' ants to protect the Queen from bees that are trying to invade the colony! If any bees reach the end or exterminate the Queen, you lose.

This project is a part of UC Berkeley's CS61A: Structure and Interpretation of Computer Programs course and utilized mainly object-oriented programming (OOP).

***All implementations from Problems 1–12 are entirely my own work.***

Since a lot of my implementations are scattered I will briefly state what I did. Planning to do Extra Challenges # 1 - 4 in the future 

***IMPLEMENTATIONS***

_Problem 1_: Overrided class attributes for 'HarvesterAnt' and 'ThrowerAnt' Class and programmed 'action' method for 'HarvesterAnt' Class 

_Problem 2_: Programmed Place.'init' to track the entrance of each 'Place' instance

_Problem 3_: Implemented 'nearest_bee' method for ThrowerAnt Class to throw leaves at nearest ant

_Problem 4_: Implemented two subclasses of 'ThrowerAnt': 'LongThrower','ShortThrower' by updating 'nearest_bee' method to check for bounds                      (throwing range)

_Problem 5_: Overrided the 'reduce_health' method in 'FireAnt' inclduing its reflective damage logic: Deals damage if hurt AND deals damage if                  killed

_Problem 6_: Implemented 'WallAnt' class from scratch

_Problem 7_: Implemented 'HungryAnt' class from scratch, includes a 'action' method

_Problem 8a_: Implemented 'store_ant" method, 'action' method, and 'can_contain' method in 'ContainerAnt' Class

_Problem 8b_: Modified 'add_to' method in 'Ant' Class to allow a container and its contained ant to occupy the same place based on some rules.

_Problem 8c_: Implemented 'ProtecterAnt' class, added a 'init' that inherits from 'ContainerAnt' Class

_Problem 9_: Implemented 'TankAnt' class from scratch, includes an 'action' method

_Problem 10_: Created a new type of 'Place' called Water. Allows waterproof insects to stay on water, but kills any insect that isn't waterproof.

_Problem 11_: Implemented 'ScubraThrower' class from scratch

_Problem 12_: Implemented the 'QueenAnt' class from scratch, includes an 'action' and 'reduce_health' method. Also created a 'double' method in                  Ant Class to use for Problem 12. 
