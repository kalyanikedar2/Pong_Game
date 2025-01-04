# 🎮 Pong Game

This is a simple **Pong Game** implemented using Python's `turtle` module. 
The game is a two-player version of the classic Pong game, where each player controls a paddle to hit the ball and try to score points.

## ✨ Features
- 👫 **Two-player gameplay**.
- 📊 **Real-time score tracking**.
- ⚡ **Smooth paddle and ball movements**.
- 🎮 **Easy keyboard controls** for both players.
w
## 🕹 How to Play
1. **Player A controls**:
   - 🔼 Move paddle up: Press `W`
   - 🔽 Move paddle down: Press `S`
2. **Player B controls**:
   - 🔼 Move paddle up: Press `Up Arrow`
   - 🔽 Move paddle down: Press `Down Arrow`
3. 🏆 **Goal**: Prevent the ball from passing your paddle while trying to score on your opponent.


  ## 🖥 Key Code Highlights
- **🕹 Paddle Movement**: Controlled using `onkeypress` events from the `turtle` module.
- **⚽ Ball Movement**: Managed by updating the ball's coordinates in the game loop.
- **💥 Collision Detection**:
  - With screen borders: Ball bounces back and reverses direction.
  - With paddles: Ball changes direction if it hits a paddle.

