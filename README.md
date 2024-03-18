# Pong Game
<sup>Game Development</sup>

## This is a remake of the classic Pong game. 
The ***game*** is played between `two players`, each controlling a paddle on their side of the screen. 

The `goal of the game` is to hit the ball with your paddle in such a way that your opponent can't return it, causing the ball to go past their paddle and score a point. 
\
The `first player to reach 10 points` **WINS** the game.

The game starts in the `'start'` state, where it _displays a welcome message_. 
\
When the user presses `Enter`, the game transitions to the `'serve'` state, where it waits for the **user** to press `Enter` again to _serve the ball_. 

In the `'play'` state, the ball is in play, bouncing between the paddles. The ball's velocity is updated based on collisions with the paddles or the screen boundaries. 
\
If the ball goes past a paddle, the game scores a point for the other player and transitions to the **'serve'** state.

If a **player** reaches `10 points`, the game transitions to the `'done'` state, where it _displays a victory message_. 
\
The user can press `Enter` to _restart the game_.

**The paddles can be moved up or down by the user using the _`'w' and 's'` keys for player 1_ and the _`'up' and 'down'` arrow keys for player 2_.**

## Run the game
### To run this code, you need to use a _Lua interpreter_ that supports the _`Love2D` game engine_. 

Here are the steps to run this code:

1. Install `Love2D`: You can download Love2D from [https://love2d.org/](https://love2d.org/) and install it on your computer.
2. Create a new directory and save the code in a file with a .lua extension, for example, `main.lua`.
3. Open a terminal or command prompt, navigate to the directory where you saved the file, and run the following command:

```lua
love main.lua
```

> [!IMPORTANT]
> ***This command will run the Love2D game engine and load your code. The game window should appear, and you can start playing the game.***.

---
### Follow Me!
💙 Instagram: [@izzyluuuuh](https://www.instagram.com/izzyluuuuh/)

---

![Pong Preview](https://github.com/izzyluuuuh/Pong/assets/103919666/cca6b708-2584-431b-a768-ef15a0a097a4)
