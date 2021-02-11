# Error Handling & Debugging

### EXECUTION CONTEXT
Every statement in a script lives in one of three execution contexts: 
 GLOBAL CONTEXT
Code that is in the script, but not in a function. There is only one global context in any page. 

* FUNCTION CONTEXT
Code that is being run within a function. Each function has its own function context.


* EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function called eva l ( )

### VARIABLE SCOPE
The first two execution contexts correspond with thenotion of scope

* Q GLOBAL SCOPE
If a variable is declared outside a function, it canbe used anywhere because it has global scope.If you do not use the var keyword when creating a variable, it is placed in global scope.

FUNCTION-LEVEL SCOPE  :
When a variable is declared within a function,it can only be used within that function. This is because it has function-level scope.

> THE STACK The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks (or piles) the new function on top of the current task.

<br>

### EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity

1. PREPARE
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined


1. EXECUTE
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements

<br>

> If a variable is not found in the variables object for the current execution context, it can look in the variables object of the parent execution context But it is worth knowing that looking further up the stack can affect performance, so ideally you create
variables inside the functions that use them.

* If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 

<br>

### ERROR OBJECTS 

these error messages are from the Chrome browser. Other browsers' error messages may vary.

* Syntax Error

SYNTAX IS NOT CORRECT This is caused by incorrect use of the rules of the language. It is often the result of a simple typo. MISMATCHING OR UNCLOSED QUOTES <br>
`document .write ("Howdyl );` <br>
`SyntaxError: Unexpected EOF`

* Reference Error
VARIABLE DOES NOT EXIST : <br>
This is caused by a variable that is not declared or is out of scope. `VARIABLE IS UNDECLARED` <br>
`var width = 12 ;` <br>
`var area = width * height ;` <br>
`ReferenceError: Can't find variable: height ` <br>

* URI Error

   INCORRECT USE OF URI FUNCTIONS
   If these characters are not escaped in URls, they will cause an error: `/ ? & I : ;`

* Type Error

    VALUE IS UNEXPECTED DATA TYPE
    This is often caused by trying to use an object or method that does not exist. 

* NaN

NOT AN ERROR <br>
Note: If you perform a mathematical operation using a value that is not a number, you end up with the
value of NaN, not a type error.

`NOT A NUMBER`
`var total = 3 * 'vary'; `

<br>

* HOW TO DEAL WITH ERRORS

there are two things you can do with the errors.

1. DEBUG THE SCRIPT TO FIX ERRORS

   If you come across an error while writing a script, you will need to debug the code, track down the source of the error,and fix it.
   You will find that the developer tools available in every major modern browser 

2. HANDLE ERRORS GRACEFULLY

    You can handle errors gracefully using try, catch,
    throw, 

        try {
        Try to execute this code }
        catch (exception) {
            If there is an exception, run this code}
        finally {
        This always gets executed 
        }

* TRY

    First, you specify the code that you think might throw an exception within the try block. If an exception occurs in this section of code, control is automatically passed to the corresponding catch block. The try clause must be used in this type of error handling code, and it should always have either a catch. If you use a continue, break, or return keyword inside a try, it will go to the finally option

* CATCH

    If the try code block throws an exception, catch steps in with an alternative set of code. It has one parameter: the error
    object. Although it is optional, you are not handling the error if you do not catch an error. The ability to catch an error can be very helpful if there is an issue on a live website.

* FINALLY

    The contents of the finally
    code block will run either way - whether the try block succeeded or failed. It even runs if a return keyword is used in the try or catch block.


    <br>


### [Back To README File](https://raghadmustafa96.github.io/reading-notes/README201)