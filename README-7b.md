# Functions, Methods, and Objects

## Creating an object 

### WAYS TO CREATE OBJECTS

* LITERAL NOTATION

        var hotel = {}
        hotel .name= 'Quay';
        hotel .rooms = 40;
        hotel.booked = 25;
        hotel.checkAvailabil ity =function()
        return this.rooms - this .booked;
        } ; 

* OBJECT CONSTRUCTOR NOTATION 

you can create a new object using combination of the new keyword and the **Object** constructor function.
next you can add properties and methods to it using dot notation.

            var hotel = new Object(); 
            hotel.name = 'Quay'; 
            hotel.rooms = 40; 
            hotel.booked = 25: 
            hotel.checkAvailability = function() { return this.rooms - this.booked; };



* The `this keyword` is used instead of the object name to indicate that the property or method belongs to the object that this function creates. 

* ARRAYS ARE OBJECTS 

   Arrays are actually a special type of object. They hold a related set of key/value pairs (like all objects), but the key for each value is its index number.  

* THE BROWSER OBJECT MODEL:

The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.

        PROPERTY                  METHOD 
        window.innerHeight       window.alert() 
        window.innerWidth        window.open()
        window.screenX
        window.location
        window.document
        window.history

* THE DOCUMENT OBJECT MODEL:

   Here are some properties of the document object, which tell you about the current page. 
            PROPERTY                   METHOD
            document.title             document.write() 
            document.lastModified      document.getElementByld() 
            document.URL               document.createElement()
            document.domain 

* DATA TYPE  
1. String
2. Number
3. Boolean
4. Undefined (a variable that has been declared, but no value has been assigned to it yet)
5. Null (a variable with no value it may have had one at some point, but no longer has a value)
6. 0bject

* MATH OBJECT 

The Math object has properties and methods for mathematical constants and functions. 

PROPERTY : Math.P
METHOD   : Math.round() 
           Mat h.sqrt()
           Math.floor()
           Math.random() 

* MATH OBJECT TO CREATE RANDOM NUMBERS 

` var randomNum = Math.floor((Math.random() * 10) + l);` <br>
   This will give you a value between 0 and 9. You then add 1 to make it a number between 1 and 10.  

   <br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-7)
