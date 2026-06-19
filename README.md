# Clown Game

## Overview

Clown Game is a Java-based single-player arcade game developed using object-oriented programming principles. The player controls a clown character and interacts with different falling objects to achieve the highest possible score.

The game includes multiple themes and worlds, such as a classic clown environment and a space-themed mode with different game objects and mechanics.

---

## Features

- Interactive graphical user interface
- Multiple game worlds and themes
- Different types of game objects
- Real-time object movement and interaction
- Object-oriented design
- Java-based game engine integration

---

## Game Objects

The game contains several interactive objects, including:

- Ball objects
- Bubble objects
- Cross objects
- Space fighter objects
- The player-controlled clown object

These objects are implemented as separate classes to allow easier extension and maintenance.

---

## Project Structure

```
ClownGameTest2/
│
├── src/
│   └── eg/edu/alexu/csd/oop/game/sample/
│       ├── Main.java                  # Application entry point
│       │
│       ├── object/
│       │   ├── BallObject.java
│       │   ├── BarObject.java
│       │   ├── BubbleObject.java
│       │   ├── ClownObject.java
│       │   ├── CrossObject.java
│       │   ├── ImageObject.java
│       │   └── SpaceFighterObject.java
│       │
│       └── world/
│           ├── Ball.java
│           ├── Bubbles.java
│           ├── Gold.java
│           ├── Space.java
│           ├── StartMenu.java
│           └── StarWar.java
│
├── engine_v3.jar
├── build.xml
└── manifest.mf
```

---

## Technologies Used

- Java
- Java Swing / AWT
- Object-Oriented Programming (OOP)
- Apache Ant
- Custom Game Engine Library

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/ClownGameTest2.git
```

2. Open the project in your preferred Java IDE.

3. Make sure `engine_v3.jar` is added to the project's libraries.

4. Build and run `Main.java` to start the game.

---

## Authors

Developed as a university programming project.
