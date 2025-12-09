1. Open CatanDriver.java and compile it
1a. if you want to play the actual game and not run a systems test, 
    comment out lines 45-55 and line 69 (they are marked with TODO)
2. make sure buildFile.txt is in the same folder as CatanDriver.java
3. run the CatanDriver.java
4. this will start the game with player 1 with a settlement on Node A,
   and player 2 with a settlement on Node D
5. you will start by controlling player 1's actions, 
   being able to take an action by inputting 1-6 in the terminal
	[1] Move along a road (a built Edge)
	[2] Build (a road, Settlement, or City)
	[3] Check where the nearest Settlement is (BFS)
	[4] Trade resources if you are at a Settlement (this option is non-functional. we didn't make it yet)
	[5] Fight a Robber adjacent to you
	[6] End your turn
6. after choosing an action, sometimes you will need to choose an option by inputting a number. Your options will be listed with a number following # (for example #2
7. keep in mind that if you move outside of the fist ring (Nodes A-F) the Nodes won't produce the same resources as they appear to 
