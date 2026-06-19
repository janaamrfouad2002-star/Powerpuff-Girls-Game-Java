# Powerpuff-Girls-Game-Java
# Powerpuff Girls Catching Game

## Overview
Powerpuff Girls Catching Game is a single-player Java game where the player controls Professor Utonium and catches falling characters from the Powerpuff Girls universe.

The objective is to catch the same Powerpuff Girl character three consecutive times to increase the score. As the difficulty increases, villains are introduced with different penalties:
- **Mojo Jojo** decreases the player's score when caught.
- **Satan** causes the player to lose a life when caught.

The player starts with three lives. The game ends when all lives are lost.

---

## Game Levels

### Easy Level
- Contains only the Powerpuff Girls characters.
- The player gains points by catching the same character three times in a row.

### Medium Level
- Introduces Mojo Jojo.
- Catching Mojo Jojo decreases the player's score.

### Hard Level
- Introduces Satan in addition to Mojo Jojo.
- Catching Satan results in losing one life.
- Features increased game speed and difficulty.

---

## Features
- Multiple difficulty levels (Easy, Medium, Hard)
- Dynamic falling objects
- Score and life management system
- Character-based gameplay mechanics
- Object-oriented game architecture
- Implementation of multiple design patterns

---

## Design Patterns Used

### Singleton Pattern
Used to ensure that only one instance of the `ObjectFactory` exists throughout the game.

### Factory Pattern
Used to create different game characters dynamically depending on the requested character type.

### Builder Pattern
Used to construct and manage different categories of game objects:
- Constant objects (background, hearts)
- Moving objects (falling characters)
- Controllable objects (Professor Utonium)

### Iterator Pattern
Used to traverse collections of game objects without exposing their internal implementation.

### Strategy Pattern
Used to implement different game difficulty levels. Each level provides its own configuration for:
- Falling speed
- Game time
- Maximum number of Powerpuff Girls
- Maximum number of Mojo Jojos
- Maximum number of Satans

---

## Technologies Used
- Java
- Object-Oriented Programming (OOP)
- Design Patterns
- Java Swing/AWT (GUI)

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/Powerpuff-Girls-Game.git
```

2. Open the project in your preferred Java IDE (such as IntelliJ IDEA or Eclipse).

3. Build and run the main game class.

---

## Project Structure

```
src/
├── Characters/
├── Factory/
├── Builder/
├── Strategy/
├── Iterator/
├── World/
└── Main Game Classes
```

---

## Authors
Developed as a Programming 2 final project.

- Nada Hassan Abdelsalam
- Jana Amr Fouad
- Hania Amr Taha
- Nada Mohamed Abdelkader Allam
