# Object Literals

* Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, 
variables and functions take on new names.

## IN AN OBJECT :

1. VARIABLES BECOME KNOWN AS PROPERTIES 
If a variable is part of an object, it is called a 
property. Properties tell us about the object, such as 
the name of a hotel or the number of rooms it has. 
Each individual hotel might have a different name 
and a different number of rooms.

2. FUNCTIONS BECOME KNOWN AS METHODS 
If a function is part of an object, it is called a method. 
Methods represent tasks that are associated with 
the object. For example, you can check how many 
rooms are available by subtracting the number of 
booked rooms from the total number of rooms. 

* Literal notation is the easiest and most popular way
to create objects. (there are several ways to create objects.) 

* You access the ptoperties or methods of an object
using dot notation.
You can also access ptoperties using square brackets.

### Example of Objects Literal :

c3/ j s/obj ect-1itera1 . j s 
var hote l = { 
name: 'Quay', 
rooms: 40, 
booked : 25, 
checkAvailability: function() { 
return this.rooms - this.booked; 
} 
} ; 
JAVASCRIPT 
var el Name = document .getElementByld('hotelName'); 
elName.textContent =hotel .name; 
var elRooms = document.getElementByid{'rooms'); 
elRooms.textContent = hotel .checkAvailability(); 



> NOTE :
If you had two objects on the same page, you would create each one using the same notation but store them in variables with different names. 


> ( References that i used )
[Duckett JS book](https://ltuc-asac.slack.com/files/U019NRDFF97/F022SGL4CKV/duckett_html__1_.pdf)