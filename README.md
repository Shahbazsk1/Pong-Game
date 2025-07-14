# Pong-Game

<h2>
  <p>This project is a recreation of the classic Pong game using Python's built-in turtle module, encapsulated with object-oriented programming (OOP).<br>
Players control paddles to bounce a ball back and forth. The goal is to prevent the ball from passing your side while trying to score on the opponent.</p>
</h2>
<h3>🕹️ Pong Game – Overview</h3>
<h4>📁 Project Structure</h4>
<ul>
  <li>The game is split into 4 main components:
    <ul>
      <li>main.py : Sets up the screen and runs the game loop</li>
      <li>paddle.py :	Defines paddle behavior</li>
      <li>ball.py :	Controls ball movement and bounce logic</li>
      <li1>scoreboard.py : Displays and updates scores</li1>
    </ul>
  </li>
</ul>
<h4>📜 1. main.py – Game Controller</h4>
<ul>
  <li>Key Features:
    <ul>
      <li>Initializes the screen using turtle.Screen().</li>
      <li>Sets up two Paddle objects (left and right).</li>
      <li>Creates the Ball and Scoreboard.</li>
      <li>Binds keypresses:
      <ul>
        <li>Up, Down for right paddle</li>
        <li>W, S for left paddle</li>
      </ul>
      </li>
    </ul>
  </li>
</ul>
<h4>🟨 2. paddle.py – Paddle Class</h4>
<ul>
  <li>Methods:
    <ul>
      <li>go_up(): moves paddle up by 20 pixels</li>
      <li>go_down(): moves paddle down by 20 pixels</li>
    </ul>
  </li>
</ul>
<h4>🔴 3. ball.py – Ball Class</h4>
<ul>
  <li>Bounces off:
  <ul>
    <li>Top/bottom wall (bounce_y())</li>
    <li>Paddle (bounce_x())</li>
  </ul>
  </li>
  <li>Speed increases slightly after each paddle hit</li>
  <li>reset_position() places the ball at center and reverses direction</li>
</ul>
<h4>🟩 4. scoreboard.py – Scoreboard Class</h4>
<ul>
  <li>Displays two scores at top of screen</li>
  <li>Updates score display on screen using update_scoreboard()</li>
  <li>Methods:
  <ul>
    <li>l_point(): increases left score</li>
    <li>r_point(): increases right score</li>
  </ul>
  </li>
</ul>
<h4>📦 Modules Used</h4>
<ul>Built-in Python Modules:
  <ul>
    <li>time :	Controls speed of game loop with time.sleep()</li>
  </ul>
</ul>
<ul>
  <li>🐢 turtle Module:
  <ul>
    <li>Python's built-in graphics library used for drawing and animation.</li>
  </ul>
  </li>
</ul>

