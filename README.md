To briefly describe my program it contains a function that is defined as a print board, with board as its parameter so it will execute every time I call it. I then define check input as a means to check if the user's input is valid, in this case only 1-9 would be valid because it is a 3 by 3 board. To make sure the inputs given remain numbers, anything besides an integer (within 1-9) will cause an error and ask the user to try again. To make sure the program can discern if a spot is taken already or not, I utilize an if statement and a condition to notify the user it is already taken but if not then the program keeps running. Going forward I created a function that translates the user's input to the corresponding row and column. Additionally I added a function which updates the players position and a boolean variable which can either be true or false depending on the statement. This outputs the player's mark ‘x’ or ‘o’ which alternates. Moving forward I checked for a winner and if it was a  draw. 
