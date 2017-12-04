# Project 1- Trace Ball

### I. Description
In this game, the player will control a square by moving their mouse cursor within the game window. The player will be chased by an NPC square that will attempt to touch the players square. If the two collide, the player will lose a life. After 3 lives are lost, the game is over.

### II. Epic And User Stories

##### Epic

I would like to create a game that 
1. As a player, I would like to be able to play the game in a browser because I would be able to play it on multiple devices.
2. As a player, I would want my character to follow my mouse cursor so that I can control it.
3. As a player, I woud want the NPC to chase my character so that the game has challenge
4. As a player, I would like to be able to see both characters so that I have a fair chance at the game
5. As a player, I would want to know when I have lost all 3 of my lives so that I know when the game is over
6. As a player, I would like to know when I have come into contact with the NPC so that I know when I am losing lives

### III. Genre
This project will be a 2D, top down, casual arcade game

### IV. Technical Details

##### Platform
I will be making the game using Javascript. This is because a requirement set out in the brief given to me buy the client was for the game to be run/played in a browser

##### Programming Language/Enviroment
I will be developing this game using Javascript as instructed in the brief. The game will be able to run on any web browser but will require a mouse to work correctly (Not touch screen compatable)

Also as instructed in the brief, I will be writing my code in Notepad. Notepad is a simple text editor that offers no helpful features like an IDE would.

##### Programming Challenges
During this project, I will need to find a solution to the following problems/challenges.
  
  - How to draw and fix objects in a canvas
  - How to make the players square follow the mouse presicely 
  - How to detect a collision between the player and the NPC
 
##### Constructing And Implementing My Code

To start constructing my code I used the internet to find out how to construct a basic canvas. In order to learn more about how the code works, my technique was to change different aspects of the code and see the results of my changes compared to the original. by doing this I am able to disect the section of code and can transfer the knowledge I gain to other functions and progamming languages. For example, once I learned how to stlye a canvas, I was able to transfer this knowlege and know how to style rectangles and otehr shapes within the game, as the code was similar.

##### Algorithms

The main alogorithm I needed to use was a collision detection algorithm to be used between the player character and the NPC. I started by researching a basic collision detection algorithm between two objects and started my process of working backwards and disecting the code in order to understand it and adapt it to fit my game. This process took alot longer than I had anticipated because disecting the algorithm was proving difficult as I was unable to achieve my desired results when changing bits of the code. Specifically, checking the co-ordinates of the two characters (collisions were being detected even though they were not visabley touching. However with persistence I was able to solve this problem.
 
##### Coding Standards 
While writing my code, I chose to use indenting rather than spacing, I chose this for two main reasons. Firstly, for me personally, using the tab button is intuative and saves time on not pressing repeatedly or holding the space button. Secondly, tabs are universal for all text editiors, therefor they will appear consistent, regardless of which text editior is used.

### V. Project Management

##### Burndown Chart

![Burndown](https://i.imgur.com/owoBcqZ.png)

As my burndown chart shows, The challenges that I had to solve took longer than I anticipated. This was due to the fact that implementing collision detection was alot more difficult than I first estimated and this in turn, pushed back my entire project. As a result of this I was unable to fully complete my 'lives' system. Apart from this setback, the game is in a playable state.

##### User Stories Tracking Chart (Which Stories Have Been Completed)

![Chart](https://i.imgur.com/W7lagJw.png)

As shown on this chart, I was able to complete 5 out of 6 of the user stories that I created. The one that I was unable to complete was being able to track how many lives the player has. This means that currently the game does not end when the player touches the NPC.

##### Flowchart

![Flowchart](https://i.imgur.com/m2HSI0D.png)

Draw Lives (Set Lives to 3): This creates a variable and sets it's value to 3, The variable is called 'lives' as this is how many                                    chances 
