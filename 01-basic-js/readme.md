what is javascript and why we used it ?

-javascript is logic based programming language where we can create our code project functionality in that.
-javascript is a high level programming language for build web pages.
-Now we used the ES6(echma script 6) version of javascript, in other words we called vanila javascript.
- runtime environment of javascript is node js.

Variable :-

- variable is container to store some data.
- in javascript we have 3 types of variables
  1. let :-
       - Let is a type of variable which is used for changing the variable name later.
       - Now these days, most of the cases we used let for creating variable.
       - Let is a block scope code so we have been using let for most of the cases.
  2. var :-
      - Var is a type of variable which is also used for changing the variable later stage.
      - Var is used in oldest browser so now a days we are don't use var most of the time.
  3. const :-
       - Const is a type of variable where we can't change our data further.
       - Const means constant to store some data like numbers, integer etc..



  task:-
   1. difference between let & var.
   2. difference between var & const.
   3. what do you mean by hoisting in javascript ?     

Rules of variable :-

 -Variable names are case sensative "a" & "A" is different.
 -Only letter,digit,underscore & $ is allowed. (not even space)
 -Only letter,underscore or $ should be 1st character.
 -reserver words cannot be variable names.

data types in javascript :-

-data type in an attribute associated with a piece of data that tells a computer system how to interpret its value.
-in data types we used "typeof" operator to know the what type of data it is.
-mainly in javascript their are 2 types of data type.

1. primitive:-
     -in javascript there are 7 types of primitive data types.
     1. Number :- number are the type of data type those it contain some numerical value.
     2. String :- string is a type og data type that can hold some character like names...
     3. Boolean :- in boolean data type we get Boolean value like true,false.
     4. Undefined :- in undefind data type the data is not define so that it will show undefined.
     5. Null :- in this data type we get null or the value means nothing.
     6. Bigint :- in bigint we will get big integer.
     7. Symbol :- in symbol we will get whole symbol as well as the value we get for the data type.

2. Non-Primitive or Reference :-
- non primitive data types are the type of data type that can hold multiple of items in a single time.
- non-primitive data types are - object,array,function.
Object :-
     - object is a non-primitive data type which can hold multiple of item in one single entity.
     - mainly objects are working on (key:value) pair.
     - The left hand side is our keys and right hand side are the values of the following object.

     ex - 

     prathama = {
          college : "GIET",
          address : "BBSR",
          age : 48,
          salary : 45000,
          carrier : "GOOD"
     } 

Operator in JS :-
 - operator are the key features to do some task or operate some task.
 - ex:- A + B
 - in the above example A & B are the operands, '+' is the operators to do the addition.
1. Arithmetic Operators :- 
    (+,-,*,/)
    modules -> %
    Exponentiation -> **
    increament -> ++
    decrement -> --

    2. unary operator:-
   Increment = ++
   Decrement = --
   3. Assignment operator :- (assign some value to the variables)
   (=, +=, -=, %=, **=)
   4. Comparison operator :- (compair the values)
        equal to -> ==
        not equal to -> !=
        equal to & type -> ===
        not equal to & type -> !==
        (>, >=, <, <=)

    5. Logical Operator :- checks the logic of the operator(true/false)
       Logical AND &&
       table of AND operator is :-
       cond 1, cond 2, res (&&)
       T + T = T
       T + F = F
       F + T = F
       F + F = F
       Logical OR ||
       Table of OR operator is :-
       cond 1, cond 2, res (||)
       T + T = T
       T + F = T
       F + T = T
       F + F = F
       Logical NOT !

conditional statement :-

- to implement some condition in the code.
- there are 3 types of conditional statements are there
1. if condition :-
    - if condition is true then statement is true otherwise false.
    syntax :-
    if(condition){
      statement
    }
2. if-else condition :-
    - if condition is true then block executed otherwise its terminate to else condition.
    syntax :-
    if(condition){
      statement
    }
3. else-is condition :-
   - It checks the condition multiple times where condition is true.
   syantax :-
   if(condition){
      statements;
   } else if(condtion){
      statements;
   } else{
      statements; 
   }           