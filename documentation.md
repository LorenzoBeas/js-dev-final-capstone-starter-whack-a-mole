### US-01 - Basic game structure
- Added title of game the theme of this game will be boop a cat instead of whack a mole so I set the title accordingly 
- Implemented 9 holes but once the game is complete i will personalize this and change moles to cats 
- Added and defined start button 
- utilized query selector to access the elements in index.js 

### US-02 - Basic game functionality: Randomness

1. Defined the random integer function this will be used by the set Delay function when the difficulty is set to hard 

2. setDelay function implemented this will dictate how fast the cats show up depending on the dificulty selected. Utilized if statements to process the dificulty parameter that is chosen and from there set the speed of the game

3. ChooseHole function also uses random integer function retrieve a random number between 0 and 8 which will mark a hole element from the holes array
 ### US-03 - Game flow

 1. populated toggleVisibility function by using thr classList.toggle() javascript function and changed the value to 'show' 

 2. Implemented showAndHide function which utilizes the setTimeout() with the provided delay again to hide the cat and then gameOver() gets called 

 3. Implemented gameover function which uses an if statement to check if the time is greater than 0 if so then showUp() gets called again so that another mole can be shown with its respective delay  until the time runs out 

 4. Implemented the start game  function which runs through a sequence of functions to set the conditions for the game flow to initialize. ClearScore, setDuration, setEventListeners, startTimer, showUp
 
