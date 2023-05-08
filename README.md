Download Link: https://assignmentchef.com/product/solved-program-converts-inches-to-yards-feet-and-inches-using-javafx
<br>
Design JavaFX application with 7 labels and one textfield where user enters input inches.  When user enters his choice and presses enter key to complete input, program outputs resulting yards, feet, and inches.

<ul>

 <li>Use class P5 that extends Application  with start method in it, and class P5Pane that extend GridPane. The only inctance variables for P5Pane class are inputInches where user enters input  inches, and three labels: outYards, outFeet, and outInches where program displays result of conversion.  Use the following names for instance variables:</li>

</ul>

private Label outYards, outFeet, outInches;

private TextField inputInches;

<ul>

 <li>All other variables should be local where needed.</li>

</ul>

<ul>

 <li>Title bar of the output window must have your first and last name</li>

 <li>Provide also UML with classes P5, P5Pane, Application, and GridPane.  The boxes for Application and GridPane can only have top part filled, since they are Java classes.  Relationships must be specified.</li>

 <li>After entering 777, the program is the returning the largest whole number of yards which is 21. (Two yards take only 21 * 36 = 756 inches)From the remainder (777 -756  which is 21) program determines the largest whole number of feet. In 21 inches there are 1 feet. (Two feet take only 2 *12 = 24 inches, only one group of 12 fits)So 21-12 is 9 and that’s how you find the remaining inches.So for input of inches the program should return  2 yards, 2 feet, and 2 inches.Follow these conversion facts:1 yard has 36 inches.1 foot has 12 inches.</li>

</ul>