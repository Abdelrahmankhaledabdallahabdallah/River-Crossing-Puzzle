# River-Crossing-Puzzle
## README.md for River Crossing Puzzle Game

This document provides information about the River Crossing Puzzle game and instructions on how to run it.

**1. Introduction**

River Crossing IQ Logic Puzzles require you to get all of the characters(crossers) across a river
in a small boat. The boat can cross the river many times to get anyone across. In our game
each character(crosser) has some properties, the most important are:
● Weight: This property represents the weight of a crosser.
● Eating Rank: This property represents the eating rank of a crosser. Crossers with higher
eating ranks can eat crossers with lower eating ranks.
We have three major categories of crossers in our game(farmers, animals, plants). Farmers
don’t eat any crosser, can’t be eaten by any crosser and can raft the boat. Animals and plants
cannot raft the boat. There are two major types of animals (carnivorous and herbivorous).
Carnivorous can only eat herbivorous but can’t eat plants. Herbivorous can only eat plants.


**2. Objectives**

* Gain experience designing object-oriented models for games.
* Learn how to draw UML class diagrams.
* Apply design patterns like Singleton, Command, Strategy, MVC, Observer, Factory, Memento, and Iterator.
* Develop user-friendly graphical interfaces.
* Understand XML parsing using SAX, DOM, or StAX.

**3. Gameplay**

The game features two challenging stories:

**Story1:**
“A farmer wants to cross a river and take with him a carnivorous, a herbivorous and
plant.”
**Rules:**
1. The farmer is the only one who can sail the boat. He can only take one passenger, in
addition to himself.
2. You can not leave any two crossers on the same bank if they can harm(eat) each other
How can the farmer get across the river with all the 2 animals and the plant without any losses?

**Story2:**
“Four farmers and their animal need to cross a river in a small boat. The weights of the
farmers are 90 kg, 80 kg,60 kg and 40 kg respectively, and the weight of the animal is
20 kg.”
**Rules:**
1. The boat cannot bear a load heavier than 100 kg.
2. All farmers can raft, while the animal cannot.
How can they all get to the other side with their animal?

**4. Game Features**

* User-friendly graphical interface with two riverbanks, characters, and a boat.
* Levels menu to choose between stories.
* Score tracking for the number of boat crossings.
* Undo and redo buttons for correcting mistakes.
* Save and load game functionality.
* Show instructions for the current level.
* Invalid move alerts.
* Solve button to automatically find a solution .

**5. Running the Game**

1. Download the code from GitHub.
2. Ensure you have Java Runtime Environment (JRE 1.8) installed.
3. Run the self-executable JAR file.

**6. Deliverables for the Project**

* Code folder.
* JAR file for easy execution.
* Implement additional design patterns.
* Create more levels for the game.
* Design a more appealing user interface.
* Report containing:
    * UML diagram.
    * Detailed design description.
    * Sequence diagram showing game execution flow.
    * GUI snapshots and user guide.
    * Design decisions list.
    * Program execution instructions.








