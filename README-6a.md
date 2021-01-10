# Object Literals

## WHAT IS AN OBJECT? 
* a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 


### IN AN OBJECT:

* VARIABLES BECOME KNOWN AS **PROPERTIES** If a variable is part of an object, it is called a property. Properties tell us about the object.

* FUNCTIONS BECOME KNOWN AS **METHODS** If a function is part of an object, it is called a method.

* properties and methods have a name and a value. In an object, that name is called a **key** .

* An object cannot have two keys with the same name. 

* The value of a property can be a string, number, Boolean, array, or even another object. The value of a method is always a function. 

* To access a property or method of an object you use the name of the object , followed by a period, then the name of the property or method you want to access this is known as dot notation .  example

        var hotel = {
        name: 'Quay',
        rooms: 40,
        booked : 25,
        checkAvailability: function() {
        return this.rooms - this.booked;
        }
        } ; 

        var el Name = document .getElementByld('hotelName');
        elName.textContent =hotel .name;
        var elRooms = document.getElementByid{'rooms');
        elRooms.textContent = hotel .checkAvailability();

* To access a property of this object, the object name is followed by a dot (the period symbol) and the name of the property that you want Similarly, to use the method, you can use the object name followed by the method name. `hotel . checkAvailability() `.

* The only things changing in the code are the values of the hotel object's properties:
            • The name of the hotel
            • How many rooms it has
            • How many rooms are booked

* The rest of the page works in exactly the same way. The name is shown using the same code.The checkAvailability() method has not changed and is called in the same way. 

<br>

### [Back](https://raghadmustafa96.github.io/reading-notes/README-6)