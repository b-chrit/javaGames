# Snake and Ping Pong Games

This repository contains two classic games, Snake and Ping Pong, implemented entirely in Java. The games make extensive use of object-oriented programming (OOP) concepts, providing a structured and modular approach to their development.

## Snake Game

### Overview
The Snake Game is a well-known arcade game where the player controls a snake that grows in length as it consumes food. The game features a game loop that handles user input, updates the snake's position, checks for collisions, and renders the game state.

### Object-Oriented Approach
The Snake Game's code is organized using classes and objects, which align with the principles of OOP. Some key OOP concepts employed in this implementation include:
- **Encapsulation:** The game components, such as the snake and food, are encapsulated within classes with well-defined methods and attributes.
- **Inheritance:** The game panel inherits from `JPanel`, and the `KeyListener` inherits from `KeyAdapter`, allowing for event handling.
- **Polymorphism:** The game panel's `paintComponent` method is overridden to handle rendering, demonstrating polymorphic behavior.

## Ping Pong Game

### Overview
The Ping Pong Game is a two-player sports simulation where each player controls a paddle to hit a ball back and forth. The objective is to prevent the ball from passing your paddle while trying to get it past the opponent's paddle.

### Object-Oriented Approach
The Ping Pong Game's implementation also adheres to OOP principles, promoting code modularity and readability:
- **Abstraction:** Game elements like the paddles and the ball are represented as objects with distinct properties and behaviors.
- **Modularity:** Different game components, such as paddles, ball, and the game frame, are organized into separate classes, making the codebase modular and easier to maintain.
- **Encapsulation:** Game elements are encapsulated within classes with private attributes and methods, exposing only the necessary functionalities.

## Usage
To run either game, compile the respective Java file and execute the compiled class:
```bash
javac snakeGame.java
java snakeGame

javac pingPongGame.java
java pingPongGame
```
