# pong
Pong Game in Python

**Create Screen**
- Height of 600px, Width of 800px
- Black background color
- Exit on click

**Create Right Paddle & Left Paddle**
- Width of 200px, Height of 100px
- Right: x_pos = 350, y_pos = 0
- Left: x_pos = 350, y_pos = 0
- Key press should move paddle up and down by 20px

**Create Ball Class**
- Width of 20px, Height of 20px
- x_pos = 0, y_pos = 0

**Detect Ball Collision w/ Wall**
- Detect collision on top at bottom
- Screen is 600px tall
- Bounce ball

**Detect Ball Collision w/ Paddles**
- Detect collision w/ paddle and bounce
- Paddles are at x = 350 and x = -350

**Detect Ball Missing Paddle**
- Calculate point scored for other player
- Reset Ball to origin and have it start in opposite direction
