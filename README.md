# VR-Maze-Game
Oculus supported immersive maze game with a gripping storyline, Developed using Unity.

Triwizard Labrynth. 

Lose the maze and the lord shall rise!

 
Theme and Game Overview

The entire theme is based on the famous sequel of ‘Harry Potter’. 
 In the maze you will have 3 lives each of which expires exactly after 3 minutes. There is a Timer that monitors the time for this purpose. After each life is last you will be taken back to the starting positing of the scene. There are coins placed that you can collect to boost you score at the end.


 
Wireframe 

Instruction Scene:
You find yourself in the middle of an old castle and to your surprise the scene tells you that your name was added into the goblet of fire. While you still take time to reciver you find more news. Being selected by the goblet mean you need to go through the maze tournament that has absolutely no way out other than finding its end. You either spend eternity there or you free yourself. 

Maze:
The maze like mentioned has 3 lives a timer and coins placed throughout the board. Collect coins as you proceed and find the trophy at the end.  Be smart enough to find clues to find the way as you proceed. Also note you have slightly more chances of making through before your first life is lost for the coins may partially guide you. 

Winning:
Once you find the trophy go toward it to free yourself. You can then either choose to reply the entire game or leave with the memory of a wonderful experience. You finally free yourself from the labyrinth and get out of the maze.

Losing:
If you don’t find the trophy before you lose all your lives, Voldemort identifies your location and it’s all “avada kedavra “. He has been watching you the whole time and all you need to do to save your life is to teleport yourself from the maze by finding the trophy.  Remember we need to grow stronger and smarter before we can fight he who is called the dark lord.


 
Game Design.
Interface
Instruction scene:
This scene has the old castle asset in the middle of which the goblet has been placed. The goblet has the fire particle system emitting fire continuously. The goblet keeps revolving and there is a spotlight flickering above it. The canvas containing the instructions is present. As we click the next button subsequent instructions can be seen.  After the final instruction the maze scene is loaded.

Maze scene:
The maze is entirely built using plane and cube (walls). The camera is placed inside the elf character asset inside which is the canvas. The canvas has the text for timer, no of coins. It has the life images and the bag of coins images to know what is what. The coins that are places all over the maze keeps rotating continuously like in a classic game so does the trophy. The trophy also has a particle system so that it seems magical. A cube is place around the trophy whose mesh is deleted. Once the character or the player enters he cube he is taken to the win scene. Also the timer freezes and changes colour from white to green. Every time the timer runs out the character is taken back to the start of the maze and the text saying that timer ran out is displayed for 2 seconds. The no of coins collected and the time taken to finish the game appears on the next scene. 



Win
This scene is the same as the starting scenes but with explosions in the sky celebrating your victory. The timer taken to finish and the no of coins collected are displayed

Lose:
The lose scene is that of a Sanctuary in which Voldemort drops from the sky saying “avada kedavra”. As he lands on the ground a huge explosion occurs that is simulated using the particle system. 

Audio: 
Instruction scene:
The scene has the Harry Potter music running in the background that totally goes with it. Audio of the fire burning around the goblet placed can also he heard.

Maze:
The main Harry Potter theme music is included in the scene . When you collect a coin you can hear the sound of a chunk of coins in a bag move. 

Lose:
When you lose Voldemort flies from the sky toward you and says “Avada kedavra!”. Also the entire scene explodes as he lands on the ground with a big explosion sound

Win:
There are sounds of the firecrackers bursting in the sky when you c the win scene.

Interaction
Use the controller to see subsequent instruction on the first scene by clicking on the “>>” button. After the last instruction you will go to the maze. Here use the touch pad in the controller to move forward, backwards and right or left.  The scene that appears once you lose also has a button giving you a chance to retry. Click on it if you wish to play again with the help of the controller. 

 
Assets and Resources

The Assets are predominantly from sketch fab. The Assets that we have used are:
-	The castle 
-	Goblet
-	Fire particle system. (for the goblet).
-	Spotlights
-	Ghost 3D model 
-	Text style(Bubble Text)
-	Coins
-	Trophy
-	Elf Character
-	Maze (Created using cubes and a plane)
-	Canvas(Contains the timer, no. of lives remaining, coins collected )
-	Voldemort
-	Explosion particle system for Voldemort. 
-	The sanctuary environment.
-	Particle system for firecrackers.
