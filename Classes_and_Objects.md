# Classes and Objects
```
Objects are an encapsulation of variables and functions into a single entity. 
Objects get their variables and functions from classes. 
Classes are essentially a template to create your objects.


class MyClass:
    variable = "blah"

    def function(self):
        print("This is a message inside the class.")

myobjectx = MyClass()

myobjectx.function()


# init()
The __init__() function, is a special function that is called when the class is being initiated. 
It's used for assigning values in a class.

class NumberHolder:

   def __init__(self, number):
       self.number = number

   def returnNumber(self):
       return self.number

var = NumberHolder(7)
print(var.returnNumber()) #Prints '7'
```
