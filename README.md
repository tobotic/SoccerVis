SoccerVis is a repo designed to test my simulation and python skills. This is meant as a fun learning exercise using ChatGPT and Gemini to help inform my thoughts and better structure my code.

SoccerVis is a 2D animation "game" that involves a user defined amount of players vs players on a 115m (120yd) x 68m (72 yd) field. It will involve the following:

- Player Class
   - Name: Player's name
   - Number: Player's number
   - Role: Player's role (i.e. Striker, Goalie, etc.)
   - Position: (x, y) coordinate tuple
   - Speed: integer representing % of max speed
   - Methods for updating position

- Ball Class
   - State: (speed, direction) tuple representing the velocity vector
   - Destination: (x, y) coordinate tuple of end position goal
   - Methods for updating position, state, and destination 

- Field Class
   - Bounds: list of (x, y) tuples representing out-of-bounds for the field
   - Methods for updating the field
