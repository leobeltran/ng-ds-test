# ng-ds-test

#Angular, Data Structures, and search algos exam

Instructions: create a new repository called ng-ds-test. Within this repo, create a README.md file. Copy and paste all of these questions into this README file and answer them.

1. Name and describe the two main operations of a stack (to add and remove data).

  A:Push and Pop in Arrays
  PUSH - to add data to the end of the stack.
  POP  - to take out data from the top of the stack.

2. Name and describe the two main operations of a queue (to add and remove data).

  A: Enqueue and Dequeue
  ENQUEUE - to insert and item to the end of the line.
  DEQUEUE - to remove item from the front.

3. Draw the tree resulting from adding the following sequence of numbers to an empty tree:
30, 45, 15, 10, 50, 40, 20, 27
--------30
---15--------45
-10--20    40--50
-------27


4. Is this tree balanced? If not, which rotation needs to be done?
A: The tree is not balanced. leftRotation(20)
--------30
---15--------45
-10--27    40--50
---20


5. Now add 29. Is the tree balanced? If not, which rotation needs to be done?
  A:adding 29 balances node 27.
--------30
---15--------45
-10--27    40--50
---20--29

6. Consider the following tree:    
  A:
  ------5  
  ---2-----8  
  -1--3  

  Now add 0 to the tree. Which one is the first node to go out of balance?
  A:2


7. How do you fix this node?
  A:rightRotation(1)

8. What are the four main steps of mergesort?

  A: Divide in two halves, Sort the left side, Sort the Right side, Merge sides together after sorting.

9. What are the four main steps of quicksort?

  A: Select a pivot point, sort elements by less to left and greater to right, sort sublist the same until recursion stops.

10. What is an angular directive?

    A: Angular directives gove functionality to your app.

11. When specifying an angular directive, you write a function which must return an object called:  

  d. Directive Object <---

12. What is the relationship between html, the $scope construct, and angular expressions?

    A: the $cope contains the model. the expressions use the variables and functions from the $cope. html packages it all together.

13. In order to send ajax requests in Angular, you need to create an angular:  

  d. $http <------

14. In order to create a service, you must use the following angular function:

  a. angularApp.controller  <-----

15. Go to my [angular projects github repo](https://github.com/Swolebrain/ng-starter-projects) and do one of them. Don't clone the repository, but rather add all the files to the folder which corresponds to your github repo. Add the files right at the root of your repo, not within a subfolder.
