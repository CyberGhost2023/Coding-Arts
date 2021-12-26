# Coding-Arts

Welcome to the official repository of Coding-Arts, which is one of the projects participating in the Winter of Code 2021.
You have to make a proposal for atleast two of the below given Problem Statements.

# PHASE 1 Questions


## Problem Statements:

*1.* Today is Ritu's birthday. Her father wants to give her a special box of chocolates as chocolate is her favorite. But to make it more interesting 
her father also bought several similar boxes filled with different pastries. Ritu doesn't like pastries, so she asked her mother to identify the correct
box at the first attempt, so she could skip eating pastries. As an advice, Ritu learned a process to identify the special box.Ritu has to arrange all the 
boxes in an increasing manner according to their weights. The box placed in the middle will be the special box. But Ritu's father knowing the fact she will 
get help from her mother has put a rule that she can't touch any box until she chooses one.He made two piles of boxes A and B. A consists n number of boxes 
and B consists m number of boxes. The boxes in each pile are placed one upon another according to their decreasing weights.
Can you help Ritu find her special box filled with chocolates?

*NB:* (n+m) will always be odd.

*Input :*
n - number of boxes in pile A
m - number of boxes in pile B
You will be given the weights present in both piles A and B.

*Output :*
Output the weight of the box containing chocolates.

## Sample testcase for problem statement 1 :

## Input 1

     6 //n
     1 3 4 7 10 12 //pile A
     7 //m
     2 3 6 15 18 //pile B

## Output 1

     6

## Input 2

     4 //n
     7 70 500 800 //pile A
     3 //m
     5 50 550 //pile B

## Output 2

     70

## Input 2

     5 //n
     330 439 551 762 950 //pile A
     4 //m
     800 1250 1400 1450//pile B

## Output 2

     800
     

*2.* Karan along with his friends is developing an application where a user can upload their cooking recipes. Now Karan wants that if user A likes
another user B’s dishes then A can follow B’s account to know all his unique dishes and styles. But the restriction is that B won’t be able to see A’s 
dishes until he follows back A’s account. You are assigned to do this task keeping in mind all the specification.(You only have to use Data Structures and Algorithm).

*Note:* A and B will be proper names like Alice, Carrie, Dabby, etc.

*Input :*
N - number of users
M - number of connections
A B - A follows B
Karan will here ask you to output any of the user's followers. So be ready for it.

*Output :*
If Karan wants to know how many followers B has you have to output the number and name of the users.
## Sample testcase for problem statement 2 :
   ## Input
     8 14
     Carrie Dabby
     Granna Tessy
     Alice Bob
     Lily Rose
     Granna Dabby
     Dabby Alice 
     Dabby Bob
     Alice Dabby
     Rose Dabby
     Rose Alice 
     Tessy Rose 
     Tessy Dabby
     Dabby Tessy
     Rose Granna
   ## Output
     You program should run for the number of times user wants now it depends on you how you implement this
     Alice 
     2
     Dabby Rose
     Rose
     2
     Lily Tessy

*3.* Kriti is a food lover and blogger. She loves to visit new food centers and blog about her experiences. She is also famous for her blogging in the city of 
Jamshedpur. One day she decided to visit all the cafeterias(N) of the city and quote her experiences in the newspaper “Hindustan Times”. You are her guide for this 
journey. In order to visit all the cafeterias, you want to know the shortest distance of all from your home. Also to save time of your guest you want to visit the 
cafeteria closet from your home, at first and then plan for the next in a similar way. Write an efficient algorithm to help Kriti.

*Input :*
N - total number of cafeterias

Also you are given the distance of all cafeterias from each other as well as from your home.

cafe1 cafe2 dist12 - Distance dist12 between cafeteria 1 and cafeteria 2 and so on.

*Output :*
You have to print the route i.e, cafeterias you are visiting sequentailly (starting from your home).

## Sample testcase for problem statement 3 :

 ## Input:
     3      // total number of cafeterias and consider cafe as numbers from 1,2,3... and home as number 0.
     0 1 2  // distance from home(0) to cafe 1 is 2 km and so on...
     0 2 3
     0 3 10
     1 2 4
     1 3 5
     2 3 20

 ## Output:
     0 0   // starting from home(0) so 0 0
     1 2   // then visting cafe1 from home by covering a distance of 2 km and so on....
     2 4
     3 9


#  [PHASE 2 Questions](https://github.com/dscnsec/Coding-Arts/blob/main/IDEA2.md) 
#  [Contributing Guidelines](https://github.com/dscnsec/DSA-Magic/blob/main/CONTRIBUTING.md)
