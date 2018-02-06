# Lab 1

## Description and guidelines
You have multiple tasks to complete.  You may work with others, however your goal should be on understanding the logic of the flow charts you are creating, and by the end feel comfortable analyzing a problem, breaking it down into steps, and be able to create a flow chart of those ideas.  You should also feel comfortable looking at a flow chart and determining if you feel it solves the problem it is for.

With this lab, you will want to use a unispace font.  One way to gain this is to put your answers betwwen lines that contain three ~ characters:

~~~
This is a unispace font, notice that 
iiii takes up as much space as
wwww.
~~~

To draw the boxes, 
* Use hyphens for the top and bottom of the statement boxes (you do not need to worry about the sides).
* Use |, +, - to draw the lines.
* Use <, >, ^, or v for the arrow heads.
* Use / and \ for the borders of conditionals (you only need to show the corners, and these do not need to line up.)
* Have your lines that go up do so to the right of your text.

Example:
~~~
-----------------------
This is the first step   <-----+
-----------------------        |
        |                      |
        V                      |
       / \                     |
      /   \                Yes |
/  If something is true \ -----+
\  and the day is       /
   a Monday
      \   /
       \ /
        | No
        v
---------------------
The last step
---------------------
~~~

## Flowchart Tasks:

#### 1. Fizzbuzz
* starting at one and incrementing by one to a number that is given, print out either the number, or if the number is divisible by 2, print "Fizz", and if the number is divisible by 3 print "Buzz" 
~~~
----------------------
import user number
n=1
---------------------
         |   
         |
         |                  ________>______________________>_____________________
         |                 |                                                    |
         |                Yes                                                   v
         |                |                                                     |
         |_<_No_<__does n = i______<_____n=n+1___<____<________                 |
         |                                                    |                 |
divide num by 6                                               |                 |
is there a remander?____no__print "FizzBuss"                  |                 |
         |                                                    |                 |
         Yes                                                  |                 |
         |                                                    |                 |
         v                                                    |                 |
        / \                                                   |                 |
      /     \                                                 |                 v
    /         \_<_No_<__does n = i______<_____n=n+1___<____<__                  |
  / i= given number\                                          |                 |
 divide the number by 2                                       A                 |
/ is there a remander ? __>____ no_>__Print "Fizz"____>_______|                 |
\                   /                                         |                 |
  \                /                                          |                 v
        \    /                                                A                 |
          \/                                                  |                 |
          |                                                   |                 |
          |                                                   |                 |
          Yes                                                 |                 |
          |                                                   |                 |
          v                                                   |                 v
          |                                                   |                 |
 divide the number by 3                                       |                 |
 is there remander ______>____no____>____Print "buzz"___>_____|                 |
          |                                                   |                 |
          |                                                   |                 |
          Yes                                                 A                 v
          |                                                   |                 |
          v                                                   |                 |
          Print "number"___>________________>_________>_____> |                 |              
                                                                          break code
 ~~~         
#### 2. Determin a students letter grade when given the %.
~~~
---------------------
import student grade
---------------------
        |
        |
        |
is the grade in 100______>______Yes____>___Print "A"______|
to 90                                                     |
        |                                                 |
        |                                                 |
        NO                                                |
        |                                                 |
        |                                                 |
is the grade in 90______>______Yes____>___Print "B"_______|
to 80                                                     |
        |                                                 |
        |                                                 |
        NO                                                |
        |                                                 |
        |                                                 |
is the grade in 80______>______Yes____>___Print "C"_______|
to 70                                                     |
        |                                                 |
        |                                                 |
        NO                                                |
        |                                                 |
        |                                                 |
is the grade in 70______>______Yes____>___Print "D"_______|
to 60                                                     |
        |                                                 |
        |                                                 |
        No                                                |
        |                                                 |
        |                                                 |
        |                                                 |
  Print "F"______>_________>____________>_______________>Break code
  ~~~
#### 3. Convert a tempature from C to F or vice versa.

#### 4. When give three numbers return the largest of them

#### 5. The game of Nim:
* This game is played between two players.
* There are piles of stones, the number of stones in each pile is known.
* Each turn a player can take any number of stones away from a single pile (they must take at least one.)
* The person who takes the last stone from the last remaining pile looses.
  
a. Create a flow chart for the optimal move for a player if there is only one pile.

b. Create a flow chart for the optimal move for a player if there are exatly two piles.

c. Can you merge these together to create a flowchart for an optimal move if there are two or less piles?  Please do so, if yes.

d. What about if there are any number of piles.

#### 6. Find the sum of the first 100 numbers
b: modify this to find the sum of the next 100 numbers when given a starting value.

#### 7. Find the nth fibonaci number
* The 0th and the 1st fibonaci numbers are both 1.
* All other fibonaci numbers equal the sum of the two before it.
  So the 2nd fibonaci number is 2, because fib(0)+fib(1) = 1+1
  Also the 10th fibonaci number is fib(8)+fib(9)

#### 8. Find the largest prime number less than a given number
