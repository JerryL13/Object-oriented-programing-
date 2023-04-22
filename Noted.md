# Object Oreiented Programming Notes 1 

i think OOP is awesome :D

```python
#example class

class person:
  def __init__(self, name):
    self.name = name
  
  def __str__(self):
    return f"Person Object called: {self.name}"
    
   def __repr__(self):
    return self.__str__()
```

## Definitions
- Encapsulation
- Polymorphism
- Override


## U3L1
- Object: Object can be a variable, a data structure, a function, or a method; therefore,in memory having a value that can be referenced by an identifier
- instance of a class where this object can be either a variavle, a function, a data structure or combination of them 

### OOP
- practicing a design thats a reuseable software system (with the creation of objects)
- focuses on the definition of data rather than the basic programming where you get the input then proccesing then an output 
- goal is the create objects that can be defined then used to help solve issues and problems 
- "OOP focuses on how to manipulate the data of the object rather than the logic required to manipulate them”
### Objects 
- a combination of data and functional code because in the real world objects have states and behaviours 
- states: the characterisitcs, measurable data of an objects( like height and hair colour)
- behavours: the functions of an objects( what is can do bark, speak etc.)
-  objects data = attributes
-  objects code = methods 

### IN python 3
-  Methods: we just declare them lke in a new function( doesnt always need to return)
-  initaitalization method is excuted as soon as an object of the class is instantiated 
-  It helps us to do any initialization for the object’s attributes
self parameter is used to denote that the method is applied and accessible for the object itself
self will also treat its own attributes as local
Double Underscore ??? → These are key hidden features of Python that allow us to do some overwriting of Python features and hidden content

#### example 
dog may have name, colour, breed etc. for attributes
dog may have bark(), eat(), sleep etc for methods 
- if we have a dogs attributes (name,colour_) then we have intance ; therefore an objects.
- class an abstract description of all objects that can be made form this set where an objects can be instantiated form (classes contains attributes)
- attributes: Objects accessible tools
- Fields: variables that belongs to an object or a class(type1: it belongs to the instance of the class,  type2: it belongs to the class itself)
- methods: functions that the objects or the objects can call
#### example for list is an object
L = [1,2,3,4]
L is an instance of a <list class>; therefore, L is an object
Features:
L[i] → indexing … L[i:j] → Slicing
functions → len(), min(), max()
operators → + and *
methods → L.append(), L.count(), L.extend(), L.sort(), L.reverse()
-----------------------------------------------------------------------------------

## U3L2
#### Key concepts
- encapsulation 
- override
- polymorphism 
 
#### Encapsulation 
- hiding information, restricting the access to a class or objects methods or attributes
  - we do this because of data protection and restricting certain methods to be callable (in python this isn't possible, we hide attributes and methods by using a double underscore __ as a prefix.)

#### Overrides
- 

U3L4

ITERABLE ObJECTS 

iterable objects: objectsthat we can iterate through like a sequence 

