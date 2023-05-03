Download Link: https://assignmentchef.com/product/solved-cs-assignment-1-implementing-langtons-ant
<br>
You will design, implement, and test a program that implements a simulation of Langton’s Ant.  For a brief explanation consider Wikipedia:  <u>https://en.wikipedia.org/wiki/Langton%27s_ant</u>.  Note that is can be considered a cellular automaton.  This means that you have an array or matrix of cells.  Each turn or step the value of each cell may change based upon a simple rule.  For the Ant there are two simple rules.




<strong>WARNING –</strong> Use the Internet to ONLY research how the ‘game’ is structured and designed.  Design and write your own program.  <strong>Do NOT</strong> <strong>use any code that you did not write for yourself</strong>.  That would be cheating.  Much of what is available is <strong>more </strong>complicated or advanced than what is required here.  It is harder to use it than to write your own.




The rules are:




<ol>

 <li>In a white square, turn right 90<sup>o</sup> and change the square to black.</li>

 <li>In a black square, turn left 90<sup>o</sup> and change the square to white.</li>

</ol>




<strong>NOTE –</strong> Think this through carefully before you start coding.




You can use a blank character for a white space.  You can use the number sign (“#”) for black.  And for the Ant?  An asterisk of course (“*”). JJ  Left ?  Right?  Those are relative directions!  How are you going to keep track of the direction the Ant is facing?  How will you “remember” what color the current cell occupied by the Ant is or was?  You will created an Ant class to help organize, hold, and manipulate this information.




You will create your design document BEFORE you start coding. The TA will grade, in part, on how well your implementation matched your design.  Remember, in your reflections document you can explain how you had to change the design because your first idea, just didn’t work.  Just explain what you learned.  Simply stated, program design is identifying the problem to be solved, identify the inputs, specify the desired output, and then develop the algorithm(s) to convert the input into the output.




Your program will prompt the user to enter the number of rows and columns for the 2D array.  Use those values to create a dynamic array of Ant objects.  You should also prompt the user for the number of steps.  Suggest values to the user.  Notice in the Wikipedia article they mention several hundred and 10000.   Use functional decomposition to develop functions to validate the input.  What parameters and criteria do these functions need?  You should start by asking the user for the starting location of the Ant.

You should add the option for the user to have a random starting location.




Note:  You should start saving utility functions for future programs you write.

Note:  For testing purposes always start the Ant at the same location.  Then try different locations.