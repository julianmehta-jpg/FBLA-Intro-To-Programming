# FBLA Virtual Pet: Cost of Care Edition

## Project Overview
This project was built for the FBLA Introduction to Programming event (2025-2026). The goal of the program is to simulate the financial responsibility and daily tasks of owning a pet. 

## Features Included
* **Customization:** Choose your pet's name and species. The game features custom keyboard ASCII art for the Dog, Cat, and Dragon.
* **Input Validation (Error Handling):** The program uses `while` loops to ensure users can only type "Dog", "Cat", or "Dragon" during setup, and `try-except` blocks to prevent crashes if a user types letters during the math minigame.
* **Needs Management:** You must balance your pet's Health, Hunger, Happiness, and Energy.
* **Financial Economy:** Work a job (solving 1-20 addition problems) to earn money. Visit the shop to buy food and medicine.
* **Cost Tracking:** The game calculates and tracks your total lifetime expenses to show the true cost of caring for a pet.
* **Consequences & Game Over:** If you do not feed your pet, its health will drop overnight. If health reaches 0, it is Game Over and your save file is deleted!
* **Data Persistence:** You can save your progress and load it the next time you open the game.

## Requirements
* Python 3.x or higher installed on your computer.
* No external or downloaded libraries are required. This script only uses built-in Python libraries (`time`, `os`, `random`, `json`).

## How to Run the Game
1. Open your computer's terminal or command prompt.
2. Navigate to the folder where this game is saved.
3. Run the following command:
   `python main.py`
4. Follow the on-screen prompts by typing the numbers that correspond to your choices!
