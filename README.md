# CSC360 Generics Wildcards
 
Your task is to finish this program. What the program does is outlined in
the comments and the main method. It contains an Employee class and a few other classes, e.g.
Programmer, that extend Employee. You will need to write four methods to make this program work:
printNames, addElements, printFavoriteLanguages, and printAll. You are required to use wildcards in
implementing these methods:

printNames will print the names of all elements of an array list of some sort of employee objects, e.g.

ArrayList<Employee> or ArrayList<Programmer>. It does not remove elements from the array list. You
are required to use an extends wildcard in the parameter list for this method.

addElements will add elements from one array list to another array list. It does not remove elements from
either array list. You are required to use a super wildcard in the parameter list of addElements.

printAll will print all of the elements in an ArrayList, using the toString method. It does not remove
elements from the array list. You are required to use an unbounded wildcard in its parameter list.

printFavoriteLanguages will print the favorite programming languages of an array list of some sort of
programmer objects, e.g. ArrayList<Programmer> or ArrayList<WebDeveloper>. It does not remove
elements from the array list. Here again, You are required to use an extends wildcard in the parameter
list.


The correct output for the program is shown as following ...
Web devs:
Sir Timothy Berners-Lee
Brendan Eich

Sys devs:
Grace Hopper
Donald Knuth

Designers:
Roberta Williams
Sid Meier

Theorists:
Shafrira Goldwasser
Stephen Cook

General devs:
Richard Stallman
Bill Joy

All employees:
Sir Timothy Berners-Lee
Brendan Eich
Grace Hopper
Donald Knuth
Roberta Williams
Sid Meier
Shafrira Goldwasser
Stephen Cook
Richard Stallman
Bill Joy

Web devs (using toString):
WebDeveloper@15db9742
WebDeveloper@6d06d69c

Objects (using toString):
42
Hello
Programmer@7852e922

Among web developers:
Sir Timothy Berners-Lee prefers JavaScript
Brendan Eich prefers JavaScript

Among all developers:
Richard Stallman prefers Java
Bill Joy prefers Java
Sir Timothy Berners-Lee prefers JavaScript
Brendan Eich prefers JavaScript
Grace Hopper prefers C
Donald Knuth prefers C