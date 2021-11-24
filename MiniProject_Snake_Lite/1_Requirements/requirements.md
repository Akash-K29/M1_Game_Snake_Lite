## Introduction:

Snake Lite is the common name for a video game concept where the player maneuvers a line which grows in length, with the line itself being a primary obstacle.

## Research:
The concept originated in the 1976 two-player arcade game Blockade from Gremlin Industries, and the ease of implementing Snake has led to hundreds of versions for many platforms. 1982's Tron arcade game, based on the movie, includes Snake gameplay for the single-player Light Cycles segment, cementing a connection between the two. After a variant was preloaded on Nokia mobile phones in 1998, there was a resurgence of interest in the snake concept as it found a larger audience

## Requirements:

1.Basic C programming.

2.Header Files

  (i)Graphics.h
  The graphics. h header file provides access to a simple graphics library that makes it possible to draw lines, rectangles, ovals, arcs, polygons, images, and strings on a graphical window. The second step is initialize the graphics drivers on the computer using initgraph method of graphics

(ii)Time.h
  In C programming language time. h is a header file defined in the C Standard Library that contains time and date function declarations to provide standardized access to time/date manipulation and formatting.

(iv)Stdio.h
  stdio. h is a header file which has the necessary information to include the input/output related functions in our program. Example printf, scanf etc. If we want to use printf or scanf function in our program, we should include the stdio. h header file in our source code.

3.Condition Statements

(i)If condition
  The syntax for if statement is as follows:
  
  if (condition) instruction;
  
  The condition evaluates to either true or false. True is always a non-zero value, and false is a value that contains zero.  Thus it will print the statement inside the block of If.

(ii)Else if condition

  The syntax for Else if statement is as follows:
   
  if(expression)
   
  {
   
  //code to be executed if condition is true
   
  }
   
  Else
   
  {
   
  //code to be executed if condition is false
   
  }
   
The if-else statement is used to perform two operations for a single condition. The if-else statement is an extension to the if statement using which, we can perform two different operations, one is for the correctness of that condition, and the other is for the incorrectness of the condition. Here, we must notice that if and else block cannot be executed simultaneously. Using if-else statement is always preferable since it always invokes an otherwise case with every if condition

(iii)Else if ladder Condition

The syntax for Else if Ladder statement is as follows:

if(condition1)

{

//code to be executed if condition1 is true

}else if(condition2)

{

//code to be executed if condition2 is true

}

else if(condition3)

{

//code to be executed if condition3 is true

}

Else

{

//code to be executed if all the conditions are false

}

The if-else-if ladder statement is an extension to the if-else statement. It is used in the scenario where there are multiple cases to be performed for different conditions. In if-else-if ladder statement, if a condition is true then the statements defined in the if block will be executed, otherwise if some other condition is true then the statements defined in the else-if block will be executed, at the last if none of the condition is true then the statements defined in the else block will be executed. There are multiple else-if blocks possible. It is similar to the switch case statement where the default is executed instead of else block if none of the cases is matched.

4.Loop Controls

(i)While loop

The syntax for While loop statement is as follows:

while(condition){

//code to be executed

}

The while loop in c is to be used in the scenario where we don't know the number of iterations in advance. The block of statements is executed in the while loop until the condition specified in the while loop is satisfied. It is also called a pre-tested loop.

(ii)For loop

The syntax for For loop statement is as follows:

for(initialization;condition;incr/decr)

{

//code to be executed

}

The for loop is used in the case where we need to execute some part of the code until the given condition is satisfied. The for loop is also called as a per-tested loop. It is better to use for loop if the number of iteration is known in advance.

## SWOT Analysis:

1.Strength:

  It can be accessible by the PC with low basic requirements and also without internet access we can play this game.
  
2.Weakness:

  It will not display a colorful graphical output, due to minimal use of graphics.
  
3.Opportunity:

  It can be developed with good Graphics to deliver with colorful UI.

4.Threats:

  No software is currently available for updation.

## 4W’s and 1H:

1.What:

  Building the Snake game.

2.Where:

  It has to be easily used by the user.

3.When:

  It has to be completed on 25th November 2021.

4.Why:

  I am developing this simple Snake Game for my mini project.

5.How:

  I am using C programming language for Developing this Simple Snake Game.
