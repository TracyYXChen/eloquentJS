# simple Mario

## Overview

The game is called DarkBlue, but like a simplified version of superMario. 

Users control the **black** player square to walk on the **white** ground to collect **golden** coins while evading **red** lava. Note there are two types of lava, one is a pool trapped by walls, while the other is dripping.

The allowed operations are left(&#8592;), right(&#8594;) and up(&#8593;). Users can hold the key longer to cover greater distance until hit by a wall (white). If the black squre touches lava, then it will be reset to the beginning position; if it collects all coins, then the map will be automatically updated to the next level. The winning is defined by conquering all levels in the `level.js` file. 
 
<img src="./examples/darkblue.png" alt="User interface" width="400" height="200" border=1px;/>

## Run the game
Just open `index.html` in a browser and play the game with keyboard.
