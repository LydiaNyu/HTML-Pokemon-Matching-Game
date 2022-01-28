## Introduction
This is a project to create a 'matching game' that will allow visitors to try and match a series of hidden Pokemon tokens. Speed is key, and the best time will be stored as the 'high score' on your computer - future players will need to try and beat that score in order to become the new matching champion! Here's a quick video that shows the basic features of the system:

## Website Address
It has already been uploaded to my school website: https://i6.cims.nyu.edu/~st3890/webdev/macro_assignment_06.html

## Requirements
Layout.  
1. A 'start' screen that introduces the user to your game and provides them with a button to start the game. This element should be visible to the user when the page loads.  
2. A 'play' screen that contains the play area as well as an indicator to show how much time has elapsed.  
3. A 'game over' screen that shows the user's score as well as the all time high score. It should also contain a button to start the game up again. This element should be invisible when the page loads.  

Setting Up the Game.  
1. Clicking on the initial 'play game' button should swap the display so that the 'play' screen is visible.  
2. Each token should visually display itself as a Pokeball.  
3. You will need to select 6 random images from this list and then assign 2 of your tokens to store these images (so that every token has a 'match').  
4. Each token should be clickable - when they are clicked they should swap to their 'secret' image.  
5. If a non-match occurs your tokens should pause for a second so the user can see them before they revert back to their non-secret image.  
6. The game should keep track of the elapsed time.  
7. When all tokens have been selected the game should transition to the 'game over' screen.  

Game Over Screen.  
1. The user's time should be displayed.  
2. The best time should also be displayed - you can do this by using localStorage to store the best time.  
3. If the user beats the best time their time should replace the best time being stored in localStorage. 
4. The user should be able to click and transition back to the 'game' screen from here -- this should reset the clock and re-randomize the game board with new tokens as well.  

Advanced Features.  
1. Leaderboard: Keep track of the 3 best scores for your game using localStorage. Allow the user to type in their name if they earn a best score and store this name in localStorage along with their time. Display this on the 'game over' screen along with their score.  
2. Game Expansion: Give the user a choice as to the size of their board (easy: 3x4 board; medium: 4x5 board; hard: 5x6 board). Update your leaderboard so that you have different "high scores" for each difficulty level.  
3. Sound: Trigger sounds when the user gets a correct / incorrect match.  
