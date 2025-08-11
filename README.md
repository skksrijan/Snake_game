# Snake_Game
COMPANY: CODTECH IT SOLUTIONS

NAME: SRIJAN KUMAR

INTERN ID: CT06DH541

DOMAIN: C++

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION:
The Snake Game is a modern C++ implementation of the classic arcade game, designed to provide an interactive and visually appealing gaming experience while showcasing fundamental concepts of game development. Built using the **SFML (Simple and Fast Multimedia Library)** framework, the project demonstrates how to integrate graphics rendering, user input handling, sound effects, and real-time game logic into a cohesive application. The primary objective of the game is simple yet challenging — the player controls a continuously moving snake that must consume food items to grow in length while avoiding collisions with its own body and the boundaries of the game window.

From a technical perspective, the project utilizes **object-oriented programming (OOP)** principles to organize game entities and logic. The snake is represented as a dynamic collection of segments, often stored in a vector or list data structure, allowing efficient insertion and removal of body parts as the snake moves and grows. The food object is placed at random positions within the playfield using pseudo-random number generation, ensuring that it does not overlap with the snake’s body. This requires collision detection logic to check for overlaps between the snake’s head and other objects in the game.

The **game loop** is the core of the application, running continuously while the game is active. This loop performs several critical tasks each frame:

1. **Event handling** — SFML’s event system captures user inputs such as arrow keys or WASD keys to change the snake’s direction. Input handling includes logic to prevent illegal moves, such as immediately reversing direction, which would cause a collision with the snake’s own body.
2. **Game state updates** — The snake’s head position is updated based on the current direction, the tail segment is adjusted, and collision checks are performed to determine if the game should end. If the snake consumes a piece of food, its length is increased, and the score is updated.
3. **Rendering** — The SFML graphics module is used to draw the snake segments, the food item, and the score display to the window. Shapes such as rectangles and circles are used to visually represent these elements, with customizable colors and sizes.
4. **Timing and difficulty scaling** — The game speed is controlled by a frame delay or delta time logic. As the player’s score increases, the movement interval is decreased, thereby increasing the game’s difficulty level dynamically.

Sound effects are incorporated using SFML’s audio module, enhancing the immersive experience. For example, a distinct sound is played when the snake eats food, and another sound is triggered when a collision results in a game-over scenario. These auditory cues provide instant feedback to the player and add polish to the gameplay.

One of the important aspects of this implementation is **collision detection**, which ensures that the game logic remains consistent. Boundary collision detection checks if the snake’s head coordinates move outside the playable area, while self-collision detection verifies if the head’s position matches any segment of the body. Both conditions lead to a game-over state, prompting the player to restart or exit.

The code structure is modular, with separate functions or classes handling different responsibilities — such as the Snake class managing movement and growth, the Food class managing position generation, and the Game class handling the main loop, rendering, and state transitions. This separation of concerns improves code readability, maintainability, and extensibility, allowing new features to be added with minimal refactoring.

This Snake Game project not only replicates a nostalgic gameplay experience but also serves as a practical demonstration of **game development fundamentals in C++**. By leveraging SFML, the project highlights how a relatively simple concept can be expanded into a polished, feature-rich application that includes graphics, animations, sound effects, input handling, and increasing difficulty levels. It is an ideal portfolio project for showcasing skills in C++ programming, OOP design, and real-time interactive application development.


OUTPUT:
![img](https://github.com/user-attachments/assets/d0696f14-b32b-4360-b1d2-c1b8c166896f)

