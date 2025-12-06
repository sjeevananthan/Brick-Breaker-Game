Brick Breaker Game

Created by Josue Argueta, Samyuktha Jeevananthan, and Ryan Yang

Computing Fundamentals for Engineers — November 2025

Project Goal

Recreate the classic Brick Breaker arcade game using Python and Pygame, focusing on:
- Clean object-oriented design
- Realistic ball–paddle physics
- Brick collision accuracy
- Multiple difficulty modes
- A polished menu + UI system

How to Run:
1. Install Pygame
pip install pygame

2. Download or Clone
git clone https://github.com/sjeevananthan/Brick-Breaker-Game

3. Run the game
python BrickBreaker.py

Requirements

Python 3.8+

Pygame 2.x
No additional files or dependencies required.

Approach

OOP structure with classes: Paddle, Ball, Brick, PowerUp
60 FPS game loop for smooth updates
Angle-based paddle bounce for more realistic control
Speed clamping prevents unstable ball acceleration
Difficulty selector (Easy / Medium / Hard)
Power-ups: Expand, Shrink, Extra Life, Multiball
Full UI: main menu, pause screen, win/lose screens

Gameplay

Move paddle: ← →
Pause: P
Return to menu (paused): M
Break all bricks to win
Don’t let the ball fall!

Status

Fully functional game with:
- Accurate collisions
- Multiple balls
- Power-ups
- Difficulty levels
- Clean restart and menu flow

Future Improvements:

Sound effects

Brick destruction animations
High-score tracking


