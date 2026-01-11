🎮 Space Shooter Game (Python + Pygame)

This is a 2D space shooter game made with Python and Pygame.

You control a spaceship and try to survive as long as possible, shoot enemies, and get a high score.

🚀 How the Game Works

You control a jet that can move around the screen

Enemies and meteors appear automatically

You can shoot bullets to destroy enemies

Some items help you, others hurt you

The game ends when your health reaches 0

🎮 Controls
Key	Action
W	Move up
S	Move down
A	Move left
D	Move right
E	Shoot
R	Reload
ESC	Quit game
❤️ Health & Score

You start with 3 health

Hitting enemies or meteors reduces health

Picking up health items restores health

Destroying enemies increases your score

When health reaches 0, the game ends

🔫 Shooting & Ammo

You have 30 bullets

Each shot uses 1 bullet

When ammo reaches 0, the gun reloads automatically

You can also reload manually with R

Reloading takes 5 seconds

👾 Game Objects
Player

The spaceship you control

Can move in all directions

Shoots bullets

Has health and score

Enemies

Fly from the right side of the screen

Reduce health if they hit you

Can be destroyed with bullets

Meteors

Fall from the top of the screen

Damage the player on contact

Items
Item	Effect
Pill	+2 health
Bad Pill	-0.5 health
Medkit	+5 health
⏱️ Spawning System

The game uses timers to spawn objects automatically:

Enemies: every 0.3 seconds

Meteors: every 1 second

Pills: every 3 seconds

Bad Pills: every 10 seconds

Medkits: every 15 seconds

🧠 Game Logic (Simple Explanation)

The game runs in a loop

Every frame:

Player movement is updated

Enemies and objects move

Collisions are checked

Health, score, and ammo are updated

If the player’s health reaches 0 → Game Over

🛠️ Technologies Used

Python

Pygame

Object-oriented programming (classes)

Sprites and collision detection

Timers and events

📂 Assets Used

The game uses image files for:

Player

Enemies

Meteors

Bullets

Background

Power-ups

(All assets must be in the same folder as the Python file)# Space-Shooter-Game
A really basic space shooter game. Basic code and lots of classes.
