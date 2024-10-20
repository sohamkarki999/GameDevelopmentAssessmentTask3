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

The processes within my game is to detect when the character has touched an obstacle which is placed on the scene or if the character has toouched the floor. Another process will be adding to the user's score whenever the character has passed an obstacle. The camera follow process will position the character at a certain point on the screen to ensure that the character has fluid movement.

#### Outputs

The bird's updated position will be shown on screen when the user starts the game. The screen will update with the current score whenever the bird successfully passes between obstacles. A "game over" message will appear when the player loses as well as sound effects for flapping, passing through obstacles, and collisions.

#### Transmission

This Flappy Bird game will not require any data transmission as this game is completely offline. However, if I were to add online leaderboards, score data would be transmitted to an online server.

#### Storage

High scores will be stored locally on the user’s device and will be shown. The game would store user settings like sound preferences such as a bar to adjust the volume.

### Functional Requirements

#### User Interaction

**Input Method:** The user will interact using mouse clicks/spacebar presses (if using a keyboard).

**User Actions:** The user action is tapping or pressing the spacebar to make the bird "flap" and rise upwards. No other user inputs are required.

**Response to Input:** When the player clicks or presses the spacebar, the bird’s travels vertically. The physics within the game then pulls it back down naturally, so the player must keep clicking to avoid obstacles.

#### Core Gameplay or Simulation Mechanics

**Flapping**: The bird ascends when the player provides an input (mouseclick or space) and descends when no input is given.

**Obstacles**: Obstacles appear with an even space between them (I am planning on making these obstacles pipes using Piskel), and the player must navigate the bird through the gaps. Colliding with obstacles or falling on the ground results in game over.

**Scoring**: The player earns points by passing successfully through the gap between obstacles. If the player is defeated on the obstacle the point will not be rewarded as they have to fully pass the obstacle.

#### Scoring and Feedback

**Scoring**: A point is added every time the character successfully passes through the pipes. The current score will be displayed at the top of the screen.
**Feedback**: When the player hits a pipe or the ground, the game provides immediate feedback with a "game over" screen. The player can then restart the game with their score being saved if it is the highest they have scored.

#### Level Progression or Simulation Stages

This section is not needed for my game as it is one endless game without any levels with the goal being the user having to get the highest score. The speed of my character will also not change depending on the character's score as seen in other games.

#### Saving and Loading Data

**Saving Data**: The game will save the player's high score localy, allowing the player to track their best score.

### Non-Functional Requirements

####



####



####

