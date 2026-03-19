# 🐾 Treat Rush - 2D Adventure Game

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SFML](https://img.shields.io/badge/SFML_3.0.0-8CC445?style=for-the-badge&logo=c%2B%2B&logoColor=white)

A 2D puzzle-adventure game developed in **C++** using the **SFML 3.0.0** library. The project heavily focuses on advanced Object-Oriented Programming (OOP) principles, memory management, and custom game physics. 

*All pixel art graphics and animations were independently designed and illustrated.*

## 🎮 Gameplay & Story
Take control of **Miți** the cat on a very important mission: reaching the fridge! Unfortunately, the path is blocked by the guard dog, **Badi**. To advance, you must explore the house, interact with various items, and solve puzzles. Stuck? Click on the helper cat, **Flafi**, for hints!

### Controls:
* **Left / Right Arrows:** Move
* **Up Arrow:** Jump
* **X:** Interact with objects
* **F:** Drop an item from the inventory
* **Left-Click on Flafi:** Get a hint
* **R:** Restart the game

## ⚙️ Technical Highlights
This project was built from scratch to demonstrate solid software engineering practices in game development:

* **Design Patterns:** Implemented the **Singleton** pattern for global state management (e.g., Game Manager) and the **Factory** pattern for dynamic entity/object generation.
* **Custom Physics:** Engineered a custom 2D collision detection algorithm (without relying on external physics engines) to handle player-environment interactions perfectly.
* **Asset Management:** Optimized the rendering pipeline for SFML to handle custom sprites, textures, and frame-rate independent animations.
