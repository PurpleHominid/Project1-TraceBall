# Project 1- Trace Ball

### I. Initiative
In this game, the player will control a square by moving their mouse cursor within the game window. The player will be chased by an NPC square that will attempt to touch the players square. If the two collide, the player will lose a life. After 3 lives are lost, the game is over.

### II. Epics and User Stories

##### Epics
1. Create a square canvas in the top left corner of the webpage that is 500px X 500px. This size is important to the function of the game as having more or less playable space and make the game easier or harder respectively.

2. Create a NPC (Non-Playable Character). The NPC will be represented by a 2D red square that is 50px X 50px with no border. The size is important for the same reason as the size of the canvas, as it can affect the difficulty of the game.

3. Create a representation for the player controlled character. This will be a 2D green square that is also 50px X 50px with no border. The size is important for the same reason as the size of the canvas, as it can affect the difficulty of the game.

4. Make the players square follow the mouse cursor instantly but only within the canvas, if the mouse was to leave the canvas the square cannot follow as this would remove challange from the game.

5. Make the NPC square follow the players mouse, but not instantly, to give the effect of the NPC chasing the player. This will provide the challenge for the game.

6. There needs to be collision detection between the player and the NPC. A collision also needs to be clearly visible to the player so they know when they have collided. This will be achieved by the players square changing colours when it touches the NPC.

##### Non-Functional Requirements
1. The colour of the canvas for this project will be pure white with a dark grey border around it that is 10px thick, to let the player see the edge of the canvas clearly.

2. While the colour of the two squares needs to be different so that the player can tell them apart, exactly what colour they need to be is not essential. For my game they will be Red for the NPC and Green for the Player

##### User Stories
1. As a player, I would like to be able to play the game in a browser because I would be able to play it on multiple devices. (1 Point)

2. As a player, I would want my character to follow my mouse cursor so that I can control it. (3 Points)

3. As a player, I woud want the NPC to chase my character so that the game has challenge. (4 Points)

4. As a player, I would like to be able to see both characters so that I have a fair chance at the game. (1 Point)

5. As a player, I would want to know when I have lost all 3 of my lives so that I know when the game is over. (3 Points)

6. As a player, I would like to know when I have come into contact with the NPC so that I know when I am losing lives. (2 Points)

##### How I Addressed The Requirements

I was initially given a project brief. The brief outlined for us what the client wanted from this project. It was up to me to determine from this brief what I needed to do in order to meet the clients needs. To do this I had to break down the brief in to more managable steps.

Firstly I broke down the project brief into what I believed to be the main tasks that I need to complete in order to meet the clients needs. These are called the 'Epics' and are the core steps to completing the project. These steps can be completed and tested independantly of one another.

The next step from breaking the task down into epics is to create user stories for the game. User stories are statements that outline an event or task that a potential user of the game would like to see happen or do in the game. By looking at the project form this perspective, I can gain a better understanding of what would work for the end user(s), it also helps me to make sure that all of the expected features are implemented correctly as I will be testing each story for bugs and errors during the course of the project.

To make sure that I meet the requirements to the deadline and to a good standard I have assigned each user story a point value for 1 to 5, with 1 being very easy and 5 being very difficult. By doing this I can prioritise what tasks I believe will be the most challenging to complete and allocate more time for myself to complete.

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
Coding standards are important to make sure your code looks neat and consistent and that you can easily come back to your code and understand what you have wrote before. It also makes it easier for multiple people to work on the same program if they use the same coding standards. Below are the coding standards I chose to use:

###### Indenting Over Spaces
While writing my code, I chose to use indenting rather than spacing, I chose this for two main reasons. Firstly, for me personally, using the tab button is intuative and saves time on not pressing repeatedly or holding the space button. Secondly, tabs are universal for all text editiors, therefor they will appear consistent, regardless of which text editior or IDE is used.

###### Line Length Under 100
I made sure that in my code, each line did not excede 100 characters in length. I chose to do this because having lines that are any longer can force the line off the edge of the screen and force me to have to scroll across and back again to edit that line of code. By not having lines very long I can save time by not having to scroll to edit.

###### Variable Names
My variable names with follow a clear naming convention. All names will start with a capital letter and will be names according to what they are storing (e.g. no variable named 'x'). If multiple variables are storing similarly named data then I will add a number to the end of the variable that starts from 1 and goes up depending on how many variables of that name there are.

###### Commenting
When adding comments to my code, I will be inserting comments above the line of code that I am talking about as to not add length to the line. By doing this I will also be sticking to another coding standard I have in place to limit the line length to 100 characters

###### Curley Brackets
My brackets will be places at the end of the line rather than starting a new line as to save space and make the document shorter, It will also make my functions easier to read.

### V. Research

### VI. Project Management

##### Burndown Chart

![Burndown](https://i.imgur.com/owoBcqZ.png)

As my burndown chart shows, The challenges that I had to solve took longer than I anticipated. This was due to the fact that implementing collision detection was alot more difficult than I first estimated and this in turn, pushed back my entire project. As a result of this I was unable to fully complete my 'lives' system. Apart from this setback, the game is in a playable state.

##### User Stories Tracking Chart (Which Stories Have Been Completed)

![Chart](https://i.imgur.com/W7lagJw.png)

As shown on this chart, I was able to complete 5 out of 6 of the user stories that I created. The one that I was unable to complete was being able to track how many lives the player has. This means that currently the game does not end when the player touches the NPC.

##### Flowchart

![Flowchart](https://i.imgur.com/m2HSI0D.png)

###### Draw Lives (Set Lives to 3):
This creates a variable and sets it's value to 3, The variable is called 'lives' as this is how many more    times the player can be caught by the NPC and not end the game

###### Draw Canvas:
This is the instruction to create a canvas on the webpage in which the game will run, the objects will be drawn within this canvas and cannot move out of it

###### Draw NPC Square at Start Position:
Creates the NPC square object at a pre-determined position on the canvas

###### Draw Players Square at Start Position:
Created the players square at a pre-determined position on the canvas, away from the NPC

###### Get Player Mouse Position:
Gathers information on where the players mouse is and stores it until it is updated

###### Update Player Square Position:
This changes the position of the players square to exactly where the mouse was last recorded

