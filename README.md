# Number-Guessing-game 

This is build using python programming language. 

<h1> Step 1 </h1>
Importing the nessesary libraries. 
<ol><li> "Random" is used to select Random Numbers </li> 
  <li> To make it interesting "tkinter" is used to provoide graphical user interface. </li>
 </ol>
 
 <h1> Step 2</h1> 
 Then create a instance "tk" which initialises the interpreter and creates the root window. 
 Then provide a window name to it and then you can style the window like mentioning the gemoerty size, background color, font etc 
 
 <h1> Step 3</h1>
 Mention the items you want in your window. Here I created a text and entry box.<br> In text box I display the messages like "Enter your name", " Guess a number"<br> 
 and in entry box I receive the entries from user. 
 
 <h1> Step 4 </h1>
 Using Random I make the program to guess one number and store it in a variable. <br>
 The to provide hints to the user I divide the number stored in the variable by 2 stored the answer in variable "n".<br> 
 Then I created a accumulator variable "sc" to keep track of the attempts make. If it is greater than 5 then you loose else you win. 
 
 <h1> Step 5 - logic </h1> 
 Using simple if and elif condition I created the game. 
 if number guessed == number guessed by the machin, then call result function. 
 else you will be provided with a hint. If number guessed if greater than variable "n" you will provided with hint saying "The number you guessed is too large divide it by two" and then again you will be redirected to a text box to guess a number. And increment "sc" that is attempt made. 
 
 <h1> Step 5 </h1> 
 In result function you will declare the results. 
 If number of attemps that is if "sc" is less than 5 the you win 
 else you loose. 
