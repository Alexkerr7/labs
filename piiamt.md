Fizzbuzz by Piia:

----------------------------
Set initial "number" to 1
----------------------------
              |
+-------------+
|             |
|            / \
|       / if number<= given max\                       -----------
|       \                      /-------------No--------| End loop|
|            \ /                                       -----------
|             |
|           Yes
|             |
|             V
|            / \
|           /   \
|   /if "number"       \
|   \is divisible by 2 /----No---+
|          \    /                |
|            \ /                 |
|             |                  |
|             Yes                |
|             |                  |
|             V                  |
|            / \                 |
|      /if also        \         |
|      \ divisible by 3/--Yes-+  |
|            \ /              |  |
|             |    ------------- |
|             |        print     |
|             |     "FIZZBUZZ"   |
|             |    ------------- |
|             |                  |
|   ---------------------        |
|     Print "Fizz"               |
|   ---------------------        |
|    |                           |
|    |                  /\       |
|    |                 /  \      V
|    |      /   if "number" is       \
|    |      \   divisible by 3       /----------No-----+
|    |                \   /                            | 
|    |                 \/                              |
|    |                   |                             |
|    |                   Yes                           |
|    |                   |                    --------------------------
|    |                   V                      print the "number"
|    |  ---------------------------             --------------------------
|    |    print "Buzz"                                 |
|    |  ---------------------------                    |
|    |              |                                  |
|    |              V                                  V
|    |           -----------------------------------------
|    +-----------|      set number 
|                |   to "number"+1
|                ----------------------------------------
|                                    |
+------------------------------------+





CELSIUS-FAHRENHEIT by Piia

--------------------------
  given temperature
--------------------------
  |                     |
  |                     |
 / \                   / \
/if temp\            /if temp\
\given in C/         \given in F/
  \ /                  \ /
   |                    |
----------------    ----------------------
print                 print
temp*(9/5)+32         (temp-32)*(9/5)
----------------    ----------------------  




LARGEST OF THREE NUMBERS by Piia

-------------------------------
  given three numbers, called
  n1, n2 and n3
-------------------------------
              |
              |
             / \
         /if n1>n2 \
         \         /----No------+
             \ /                |                       
              |                / \                     
             Yes           /if n2>n3\              
              |            \        /-------No----------+
             / \               \ /                      |
       / if n1>n3  \            |                       |    
       \           /           Yes                      |
         \        /             |                       |
          \      /          ---------------             | 
           \    /            print n2                   |
            \  /             ----------------          ---------------
             \/-----------------------No---------------|print n3
             |                                         ---------------
            Yes
             |
  -----------------
    print n1
  -----------------
