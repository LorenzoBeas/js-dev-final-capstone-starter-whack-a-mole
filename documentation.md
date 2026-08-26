### US-01 - Basic game structure
- Added a title for the game. The theme of this game will be Boop a Cat instead of Whack-a-Mole, so I set the title accordingly.
- Implemented 9 holes. Once the game is complete, I will personalize it and change the moles to cats.
- Added and defined the start button.
- Utilized query selectors to access the elements in index.js.

### US-02 - Basic game functionality: Randomness

1. Defined the random integer function. This will be used by the setDelay function when the difficulty is set to hard.

2. Implemented the setDelay function. This dictates how fast the cats show up depending on the difficulty selected. I utilized if statements to process the difficulty parameter and set the speed of the game.

3. The chooseHole function also uses the random integer function to retrieve a random number between 0 and 8. This number selects a hole element from the holes array.
 ### US-03 - Game flow

 1. Populated the toggleVisibility function by using the classList.toggle() JavaScript method with the value 'show'.

 2. Implemented the showAndHide function, which uses setTimeout() with the provided delay to hide the cat. After that, gameOver() is called.

 3. Implemented the gameOver function, which uses an if statement to check if the time is greater than 0. If it is, showUp() is called again so another mole can be shown with its respective delay until the time runs out.

 4. Implemented the startGame function, which runs through a sequence of functions to initialize the game flow: clearScore, setDuration, setEventListeners, startTimer, and showUp.


 ### US-04: Whack!

 1. Utilized the += operator to increment the score by 1 point and used score.textContent to change the text inside the HTML element "score".

 2. Utilized the assignment operator to set the score to 0 in the clearScore function.

 3. For the whack event, I passed in the updateScore function to be executed.

 4. For the event listener function, there needs to be one listener per mole, so I utilized a forEach function and added the whack event handler to each mole.


 ### US-05: Timer

 1. Set the timer using the setInterval JavaScript method by passing updateTimer as the function and 1000 as the interval in milliseconds.

 2. Implemented the updateTimer function by using an if statement to check if the time is greater than 0. If true, it subtracts 1 from the value and uses timerDisplay.textContent to update the text inside the timer element.
 

 ### US-06: Originality

 1. I changed the theme of this game to be called boop a cat instead of Whack a mole, background setting takes place in a cozy lofi bedroom and I adjusted the song to match the aesthetic 

 2. I also changed the moles to be cats
