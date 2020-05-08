# Encapsulation-
Why encapsulation is important? How you can implement it in python?

Importance of encapsulation:-

Encapsulation is an Object Oriented Programming concept that binds together the data and functions that manipulate the data, and that keeps both safe from outside interference and misuse. Data encapsulation led to the important OOP concept of data hiding.

Encapsulation helps in isolating implementation details from the behavior exposed to clients of a class (other classes/functions that are using this class), and gives you more control over coupling in your code.

Encapsulation helps us in binding the data(instance variables) and the member functions(that work on the instance variables) of a class. Encapsulation is also useful in hiding the data(instance variables) of a class from an illegal direct access.

Implementation of encapsulation in python:-

Encapsulation in Python. Encapsulation is one of the fundamental concepts in object-oriented programming (OOP). It describes the idea of wrapping data and the methods that work on data within one unit. ... A class is an example of encapsulation as it encapsulates all the data that is member functions, variables, etc.


An example of encapsulation in Python:-

The wrapping up of data and functions into a single unit (called class) is known as encapsulation. Data encapsulation is the most striking feature of a class. The data is not accessible to the outside world, and only those functions, which are wrapped in the class, can access it. These functions provide the interface between the object’s data and the program. This insulation of the data from direct access by the program is called data hiding or information hiding.

program:-
class Encapsulation:
    __name = None
    def __init__(self, name):
        self.__name = name
   def get_name(self):
        return self.__name
 pobj = Encapsulation('Rocky')
print(pobj.get_name())
 
Output:-
Rocky
