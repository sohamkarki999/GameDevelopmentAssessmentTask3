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

**Input Method**: The user will interact using mouse clicks/spacebar presses (if using a keyboard).

**User Actions**: The user action is tapping or pressing the spacebar to make the bird "flap" and rise upwards. No other user inputs are required.

**Response to Input**: When the player clicks or presses the spacebar, the bird’s travels vertically. The physics within the game then pulls it back down naturally, so the player must keep clicking to avoid obstacles.

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

The game will save the player's high score localy, allowing the player to track their best score.

### Non-Functional Requirements

#### Usability Requirements

The user interface should be simple and intuitive, allowing players to immediately understand the game's mechanics. A brief, in-game tutorial or on-screen prompts should explain how to control the bird (e.g. clicking to keep it in the air) for first-time users. The UI should include clear visual feedback when the bird collides with an obstacle or the ground, as well as a restart button to make the game easily understandable.

#### Compatibility Requirements

The game must be compatible for PC and Mac users. It should utilise mouse and keyboard controls and the game should be designed to run smoothly on different screen sizes, adapting the resolution and layout to maintain a consistent experience across screen types.

#### Reliability and Availability Requirements

The game should be reliable, being up at least 99% of the time, ensuring it is available for users at almost all times (1% for minor bug fixes, game changes etc.). Since the game is offline, it should not rely on any network services. The game should include error handling mechanisms to prevent crashes, especially when the bird collides with obstacles or when restarting the game.

### Consideration of Social and Ethical Issues

#### Definitions

**Equity**: Equity refers to the fair treatment of all players by ensuring that everyone has equal access to gameplay opportunities, resources, and support.

**Accessibility**: Accessibility means designing the game to be usable by all individuals of all abilities. This includes implementing features that allow players to customise their experience, such as alternative controls, visual adjustments, and audio support, ensuring that everyone can enjoy and engage with the game effectively.

#### Accessibility

My game will be usable by all individuals and to enhance accessibility, I will integrate features such as customisable controls, which allow players to adapt gameplay mechanics to their needs, whether through keyboard or mouse. Additionally, incorporating visual adjustments, such as color contrast settings and the option for larger text, can help accommodate players with visual impairments. Subtitles for instructions can also help players who are deaf.

#### Privacy and Data Protection

It is vital to ensure that information such as the user's high score is stored securely and only with the consent of them. I will have to implement clear privacy policies that inform players about what data is collected, how it will be used, and how it will be protected, whcih will be accessable through a link on the splash screen. Using encryption for stored data can help build trust and ensure that my game will comply with data protection regulations. Safeguarding personal information such as their name for their high score is essential to maintain the integrity of my game and protect user privacy.

#### Fairness and Representation

To promote fairness and representation in my game, I will ensure that the character and game overall will reflect a diverse range of backgrounds and experiences. I will aim to create a relatable and multifaceted character that resonate with a broad audience without any harmful sterotypes related to gender, race or culture.

#### Mental and Emotional Well-Being

I need to consider the potential impact of my game on user's mental health. I will avoid including distressing content, such as excessive violence or flashing bright colours that could trigger anxiety or negative emotions. Instead, I plan to design the game to promote a positive and enjoyable experience, using harmless visuals made in Piskel and encouraging gameplay mechanics. Incorporating elements of reward will enhance player satisfaction as they pass through obstacles and gain a higher score which contributes to a sense of well-being.

#### Cultural Sensitivities

I will be mindful of cultural sensitivities in my game’s content. I understand that symbols, themes, or narratives that may be appropriate in one culture can be offensive or misunderstood in another. I will conduct thorough research to understand the cultural implications of the elements I include in my game, ensuring they are respectful and inclusive. This approach will help prevent unintentional harm and backlahs on my game and foster positive feedback from a diverse player base.