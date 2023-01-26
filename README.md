In this exercise, you’ll turn a non-OO-designed version of the game Connect Four into a more featureful, OO version.

Part One: Make Game Into a Class
--

You should end up with all of the code being in the Game class, with the only other code being a single line at the bottom.

Part Two: Small Improvements
--

Make it so that you have a button to “start the game” — it should only start the game when this is clicked, and you should be able to click this to restart a new game.

Add a property for when the game is over, and make it so that you can’t continue to make moves after the game has ended.

Part Three: Make Player a Class
--

Make it so that there is a Player class. It should have a constructor that takes a string color name (eg, “orange” or “#ff3366”) and store that on the player instance.

The Game should keep track of the current player object, not the current player number.

Update the code so that the player pieces are the right color for them, rather than being hardcoded in CSS as red or blue.

Add a small form to the HTML that lets you enter the colors for the players, so that when you start a new game, it uses these player colors.
