## Decisions and Loops

## SWITCH STATEMENTS 
A switch statement starts with avariable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

`switch (level) {` <br>
`case 'One ':` <br>
`title= 'Level 1 ' ;` <br>
`break;` <br>
`case 'Two':` <br>
`title= ' Level 2 ' ;` <br>
`break;` <br>
`case ' Three' :` <br>
`title = 'Level 3' ;` <br>
`break ;` <br>
`default :` <br>
`title= 'Test';` <br>
`break;` <br>
`}` <br>

 Here, the variable named 1 eve l is the switch value. If the value of the l eve 1 variable is the string One, then the code for the first case is executed. If it isTwo, the second case is executed. If it is Three, the third case is executed. If it is none of these, the code for the defaul t case is executed. <br>

At the end of each case is the break keyword. It tells the JavaScript interpreter that it has finished with
this switch statement and to proceed to run any subsequent code that appears after it. 

SWITCH
* You have a default option that is run if none of the cases match.
* If a match is found, that code is run; then the break statement stops the rest of the switch statement running 

<br>

## LOOPS
Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false. There are three common types of loops:  

1. FOR  
If you need to run code a specific number of times, use a for loop. (It is the most common loop.) In a for loop, the condition is usually a counter which is used to tell how many times the loop should run.

1. WHILE 
f you do not know how many times the code should run, you can use a while loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as the condition is true.

1. DO WHILE 
The do...while loop is very similar to the while loop, but has one key difference: it will always run the statements inside the curly braces at least once, even if the condition evaluates to false.

<br>

## TYPE COERCION and WEAK TYPING

If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error. JavaScript can convert data types behind the scenes to complete an operation. This is known as **type coercion** . For example, a string 'l ' could be
converted to a number 1 in the following expression:(' 1' > 0). As a result, **the above expression would evaluate to true** 
JavaScript is said to use weak typing because the data type for a value can change. Some other languages require that you specify what data type each variable will be. They are said to use strong typing. Type coercion can lead to unexpected values in your code (and also cause errors).

>  **NaN** is a value that is counted as a number. You may see it when a number is expected, but is not returned, e.g  ('ten' /2) results in NaN.

<br>

## TRUTHY & FALSY VALUES
Due to type coercion, every value in JavaScript can be treated as if it were true or false.


### FALSY VALUES

**Falsy values** are treated as if they are false. The table to the left shows a highScore variable with a series of values, all of which are falsy.

* var highScore = false;       -> The traditional Boolean false
* var hi ghScore = O;           -> The number zero
* var highScore = 10/'score' ;  -> NAN 
* var highScore;                -> A variable with no value assigned to it 

### TRUTHY VALUES 

**Truthy values** are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true.

* TRUTHY VALUES                 -> The traditional Boolean true
* var highScore = l;            -> Numbers other than zero
* var highScore = 'carr ot' ;   -> Strings with content
* var highScore = 10/5;         -> Number calculations
* var highScore = 'true';       -> true written as a string
* var highScore = '0' ;         -> Zero written as a string

<br>

## CHECKING EQUALITY and EXISTENCE 

#### EXPRESSION
(false == 0)    true  <br>
(false === 0)   false <br>
 
(false == '' ) true  <br>
(false === '') false <br>

(0  == '')  true <br>
(0 === '')  false  <br>
(undefined == null) true <br>
(null == false) false  <br>
(undefi ned == false) false <br>
(null == 0) false <br>

(Nan == null) false <br>
(NaN == NaN)  false <br>

<br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-3)

