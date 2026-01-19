**Status:** ✅ Completed

# The Boggle Monster Game

A text-based adventure game written in Java where players explore caverns, collect weapons, fight monsters, and attempt to defeat the Boggle Monster.

## Author Information

- **Author:** Rohan Bhagat
- **Date:** 10 December 2024
- **Version:** 3
- **Level:** 6

## Game Overview

You are in a cavern lit only from the entrance, and your task is to capture the Boggle Monster! Explore different locations, search for objects and weapons, battle monsters, and collect points as you progress through the game.

## Features

- **Interactive Text-Based Gameplay:** Navigate through multiple cavern locations
- **Inventory System:** Collect weapons and objects throughout your adventure
- **Monster Combat:** Engage in turn-based combat with various monsters
- **Point System:** Earn points by collecting objects and defeating monsters
- **Multiple Locations:** Explore 5 different caverns, each with unique challenges

## Game Locations

1. **Library Square** - Contains the Invisibility Cloak and Cookie Monster
2. **Ifor Evans** - Contains Batman Utility Belt and Space Jam Lebron
3. **The Canal** - Contains Captain America Shield and Thanos
4. **Queens Building** - Contains Blood Gauntlet and Melika
5. **Pooley House** - Contains Points and the final boss, Boggle Monster

## How to Play

1. **Start the Game:** The game begins by asking for your name
2. **Choose a Location:** Select a cavern to explore from the menu
3. **Explore:** Once in a location, you can:
   - Search for objects (collect weapons/items and gain points)
   - Search for monsters (engage in combat)
   - Exit the location (return to the main menu)
4. **Combat:** When fighting monsters:
   - Choose a weapon from your inventory
   - Deal damage until the monster is defeated
   - Earn points upon victory
5. **Progression:** Collect items, defeat monsters, and build your inventory to prepare for the final battle with the Boggle Monster

## Requirements

- Java Development Kit (JDK)
- Java compiler (javac)
- Java Runtime Environment (JRE)

## How to Run

1. Extract the complete program from the notebook (Cell 44)
2. Save it as `BoggleMonster.java` on your local computer
3. Compile the program:
   ```bash
   javac BoggleMonster.java
   ```
4. Run the program:
   ```bash
   java BoggleMonster
   ```

## Game Mechanics

- **Starting Points:** Players begin with 20 points
- **Random Attributes:** Object points, damage values, and monster health/points are randomly generated
- **Inventory Management:** Your inventory grows as you collect items from different locations
- **Monster Health:** Each monster has varying health levels (150-400 HP)
- **Combat System:** Use collected weapons to deal damage to monsters

## Project Structure

The game consists of three main classes:

- **CavernRecord:** Represents individual caverns with their attributes (location, objects, monsters, points, damage, health)
- **CavernArray:** Container class for managing multiple cavern records
- **BoggleMonster:** Main game class containing all game logic and methods

### Key Methods

- `main()` - Entry point of the game
- `createCavern()` - Creates individual cavern records
- `createCavernArray()` - Initializes the cavern array
- `initializeCaverns()` - Populates caverns with game data
- `whileLoop()` - Main game loop for location selection
- `exploreCavern()` - Handles exploration within a location
- `fightMonster()` - Manages combat mechanics
- `displayInventory()` - Shows player's current inventory
- `addToInventory()` - Adds items to player inventory
- `askName()` - Gets player name input
- Input validation methods: `inputString()`, `inputInt()`, `isPositiveInteger()`, `isDigit()`

## Notes

- This program compiles and runs in JHUB
- The program follows Level 6 coding standards
- All code is properly indented and commented
- Variables are defined within methods
- The program includes screen output and keyboard input
- Full literate documentation is available in the notebook

## Development Notes

- Added code to ask for age and compare with its own age
- Updated to new style guide
- Added note about backup
- Testing full program
- Added missing method in full program

---

**Good luck defeating the Boggle Monster!**
