# Game Developement Assessment Task 3 - Soham Karki

## Identifying and Defining

### Identifying a Need

#### Game Idea

I have decided on creating a '2D Platformer' game which is very similar in nature to flappy bird.

#### Brainstorming

* Create a 2D platformer with a focus on skill-based gameplay.
* Make the game for both casual and experienced players at platformer games.
* Focus on simple yet effective controls and physics-based movement.
* Add unique features like collectibles to make the game more engaging.
* The game should be visually appealing with a thematic design to a story or issue.

#### The Need

The need for my game lies in the demand for accessible yet engaging 2D platformers that adhere to a broad audience's standards. There is a gap in the market for games that gradually ramp up in difficulty while allowing players of different skill levels to enjoy the experience. Players want a game that is challenging enough to keep them interested but not so difficult that it becomes frustrating, which my game will offer as it will be endless and will offer hours of fun.

#### Problem Statement

Many existing platformer games either offer challenges that are too simple, losing tzhe interest of experienced players, or are too difficult from the start, causing casual gamers to lose interest quickly. My game aims to address this by balancing difficulty, offering an evolving learning curve that starts off easy but gradually introduces more complex challenges. This allows players to improve their skills progressively while keeping the gameplay engaging.

#### Evidence of Development Skills

For my 2D Platformer game I will be using Unity, which is well-suited for creating games and has a vast array of learning resources. I will be using C# scripting to handle character movement, collision detection, and physics-based interactions. I am following this [Flappy Bird YouTube Tutorial](https://youtu.be/ihvBiJ1oC9U) to aid me in mkaing my game. I will be applying game development concepts, like balancing difficulty and player progression, through thorough testing and feedback. I will be either leveraging Unity’s asset store or creating custom pixel art on Piskel for the game’s visuals, ensuring a consistent and engaging aesthetic which matches the game's theme.

### Requirements Outline

#### Inputs

User inputs for my 2D Platformer game will include the arrow keys for the character to jump as well as using the space bars and mouse clicks as an alternative to the jump button.

#### Processing

The processes within my game is to detect when the character has touched an obstacle which is placed on the scene or if the character has toouched the floor or the ceiling. Another process will be adding to the user's score whenever the character has passed an obstacle. The camera follow process will position the character at a certain point on the screen to ensure that the character has fluid movement.

#### Outputs

The bird's updated position will be shown on screen when the user starts the game. The screen will update with the current score whenever the bird successfully passes between obstacles. A "game over" message will appear when the player loses as well as sound effects for flapping, passing through pipes, and collisions.

#### Transmission

This Flappy Bird game will not require any data transmission as this game is completely offline. However, if I were to add online leaderboards, score data would be transmitted to an online server.

#### Storage

High scores will be stored locally on the user’s device and will be shown. The game would store user settings like sound preferences such as a bar to adjust the volume.

### Functional Requirements

#### User Interaction