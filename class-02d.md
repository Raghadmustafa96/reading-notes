# Decisions and Loops

## Comparison and logical operators: 

You can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: true or false.


* IS EQUAL TO 
`==`
This operator compares two values (numbers, strings, ar Booleans) to see if they are the same.


* IS NOT EQUAL 
`! =`
This operator compares two values (numbers. strings, or Booleans) to see if they are not the same.


* STRICT EQUAL TO 
`===`

This operator compares two values to check that bath the data type and value are the same.

* STRICT NOT EQUAL TO This operator.  
`! ==`
compares two values to check that both the data type and value are not the same. 

and also have `>, <, >=, <=`

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


### [Back To README File](https://raghadmustafa96.github.io/reading-notes)


