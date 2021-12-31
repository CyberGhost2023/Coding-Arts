# Phase 2 Questions

## Problem Statement 4:

In the city of joy kolkata, riya and her friends stay in different buildings each building has a unique number which is called building code,buildings are situated 
in a certain manner that if a building with its building code is situated at certain position then it's neighbouring buildings in the forward direction will be at most 
2 and in the backward direction 1. You have to help Riya to find no of turns(building codes that come along her way) if she wants to go from one friend's house (building
code n) to the other(building code m) if she moves in a straight line i.e. she does not take any turns, then print output -1.

![woc4](https://user-images.githubusercontent.com/61093320/147410632-800d7e4a-371c-4029-8574-83acbc16564e.png)


### *Input Pattern:*
 input 1: string representing the tree ( the values in the string are in the order of level order traversal of the tree where , numbers denote node values , and
 a character "N" denotes NULL child.
 
 input 2: space separated data values n and m  of 2 nodes.
 
 
 ### *Output Pattern:*
  no. of turns (building codes from n to m that come while she was taking turns)
  -1 if riya did not took any turn.

### Sample testcase for problem statement 4 :


  ### Input:
      Input 1: 1 2 3 4 5 6 7 8 N N N 9 10 N N
      Input 2: 5 10
      

   ### Output 
      4 
      
      
## Problem Statement 5:

Karan is thankful to you for helping him. Now karan wants to add a feature of suggestion but initially he wants to implement it in a simpler way. The requirements are if A wants to follow B's account then in the suggesstion you have to output those users who follows B but are not followed by A.

### *Input Pattern:*
n - number of users

m - number of connections

m lines follows A B ie A is following B

x - number of new connections

x lines follows C D i.e, C's request to follow D

### *Output Pattern:*
x lines each line containing the names of users who follows D but not C.

### Sample testcase for problem statement 5 :

  ### Input:
    8 13
    Carrie Dabby
    Granna Tessy
    Alice Bob
    Lily Rose
    Granna Dabby
    Dabby Alice
    Dabby Bob
    Alice Dabby
    Rose Alice
    Tessy Rose
    Tessy Dabby
    Dabby Tessy
    Rose Granna
    2
    Dabby Granna 
    Tessy Alice

  ### output
    Rose
    0
   
   
## Problem Statement 6:

Kriti's guide is thankful to you and now he is on his new tour plan. The guide is planning to visit some cities and explore more about his interest of travelling and guiding. But here comes a problem before him and he wants you to solve it. The problem is, he have to follow a map given by the experienced traveller. According to the map, if you want to visit city X then earlier to that you must visit city Y, then only you can visit city X and similar to this, there are restrictions for some other cities too. Now the guide is confused from where to start and how to visit the cities, so that he could visit all the cities. So, you need to provide a path in the order which will help the guide to achieve his goal. It may happen that there is no such path which will help the guide to visit all cities.

### *Input Pattern:*
totalCities - Total Number of cities in the map

cityX,cityY - CityY must be visited prior to cityX
.......

### *Output Pattern:*
cityY cityX ..... // the order in which guide is going to visit the cities


### Sample testcase for problem statement 6 :

  ### Input: 
      2
      Kolkata Durgapur
     
   ### output    
      Durgapur Kolkata
   
   
      
