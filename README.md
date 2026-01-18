Jet Shooter Game

Jet Shooter is a 2D arcade-style shooting game built with Python and Pygame. Players control a jet fighter, avoiding meteors, collecting power-ups, and battling increasingly difficult enemies and bosses.

Features

Player Mechanics: Move freely with W, A, S, D keys and shoot with E.

Enemies & Bosses:

Regular enemies spawn frequently.

Three progressively stronger bosses appear as your score increases.

Power-ups:

Health packs (Medkit) restore player health.

Ammo pickups increase your bullet count.

Pills and bad pills affect health and speed.

Dynamic Obstacles: Meteors fall from the top of the screen and damage the player.

Ammo System: Limited ammo with reloading mechanic for added strategy.

Score Tracking: Score points by destroying enemies and bosses.

Game Over & Restart: If health reaches zero, players can restart or return to the main menu.

Controls
Action	Key
Move Up	W
Move Down	S
Move Left	A
Move Right	D
Shoot	E
Reload	R
Start Game	Space
Restart	Enter
Return to Menu	F
How to Run

Install Pygame if not already installed:

pip install pygame


Make sure all image assets are in the same directory:

background.png, background3.png, jet.png, player2.png, player3.png, enemy2.png, Boss.png, boss2.png, boss3.png, Bullet.png, Ammo.png, Medkit.png, Pill.png, Badpill.png, Meteor.png, gameoverscreen.png

Run the game:

python main.py

Notes

The game scales to a 1400x788 screen resolution.

Boss fights modify the player’s abilities and reload times.

Enjoy progressively harder challenges as your score increases!
