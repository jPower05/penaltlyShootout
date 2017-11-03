# Penalty Shootout
Penalty Shootout style game developed using the Babylon.js gameEngine

# FEATURES<br />

# Particle Systems<br />
  * Particle system plays when celebrating a goal scored. <br />
  
# Environment<br />
  * Sky box around the scene <br />
  * Textured walls/pendulum/ground <br />
  * Point light lights up the scene <br />
  
# GUI Elements <br />
  * Slider GUI that sets the ball direction <br />
  * GUI Button to fire the ball <br />
  * GUI Labels to display score and highscore <br />
  
# Complex Physics Imposters<br />
  * Ball collisions are dealt with by giving objects physics imposters<br />
  * Ball is shot by giving it a linear velocity impulse in a specific direction<br />
  * Pendulum moves by giving it an initial impulse in the x direction. Given smaller impulse each frame to keep it going<br />
  * Pendulum created by using a distance joint between the pendulum anchor and pendulum ball <br />
  
# Camera
  * Main camera is an Arc Rotate camera <br />
  * Camera target is the current ball position <br />
  * Player can rotate the camera using the arrow keys. Zoom in/out using the mouse wheel <br />
  * Camera moves to the position of the last spawned ball so the player has a good view of the target <br />
  
  
# Audio 
  * Sound plays when a ball is kicked/fired <br />
  * Sound plays when a goal is scored <br />

# GENERAL GAMEPLAY
  * Players spawns into the game <br />
  * Ball is spawned in front of them <br />
  * Players aim is to aim the ball using the slider into the goal <br />
  * The must then time their hit of the fire button in order to avoid the pendulem blocking the goal <br />
  * If they score a congradulatory sound is played and the score is increased <br />
  * The player is all the time trying to better their previous high score <br />

  
  
  

