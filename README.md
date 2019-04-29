# unit-4-game
Homework 4

Psuedo Coding

HTML:
- Directions based on image/directions.
- Play button? Or should it start up upon page load?
- Announcement that appears when user wins/losses.
- Random number and total score.
- Tally of wins and losses.
- Four images of crystals that can be clicked on to add points to the total score.

CSS:
- Different background colors/font colors for different divs.

JQuery:
    // Use a function to assign random number for each crystal (between 1,12)
    // push the value of the goalNumber to the Dom, but not the crystal values
    // Create function to restart the game and call it when the game is won or lost.
    // Create on-click function to assign values to each crystal by ID.
    // Add the value of the crystal clicked on to the totalScore
        // Send totalScore value to DOM
            // If totalScore equals goalNumber (win)
                // Add a win to the wins variable
                // Send wins tally to DOM
                // Send announcement to DOM
                // reset game with restartGame function
            // If totalScore is greater than goalNumber (loss)
                // Add a loss to the losses variable
                // Send losses tally to DOM
                // Send announcement to DOM
                // reset game with restartGame function

