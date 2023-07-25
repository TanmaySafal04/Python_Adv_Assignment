Q1. What is the purpose of Python&#39;s OOP?

Q2. Where does an inheritance search look for an attribute?

Q3. How do you distinguish between a class object and an instance object?

Q4. What makes the first argument in a class’s method function special?

Q5. What is the purpose of the __init__ method?

Q6. What is the process for creating a class instance?

Q7. What is the process for creating a class?

Q8. How would you define the superclasses of a class?

# Answers

#1 What is the purpose of Python's OOP?

OOPs or Object-Oriented-Programming approach makes the program efficient and easy to understand. It allows code resuability, data is safe through abstraction.

#2  Where does an inheritance search look for an attribute?

An instance search first looks in the instance object and then in the class where the instance was created and after that in all other higher classes

#3 How do you distinguish between a class object and an instance object?

Class is like a blueprint to build the object and object is the product of that blueprint.

#4 What makes the first argument in a class’s method function special?

First agrument is special as all the methods called by the instance of the class must be called with this argument as their first argument. It points to the instance of the class.

#5 What is the purpose of the init method?

__init__ method is called when an object is created from the class and it allow the class to initialize the attributes of a class.

#6 What is the process for creating a class instance?

instance/object_name=classname(parameter if any)

#7 What is the process for creating a class?

class class_name:
   attribute/methods 

#8  How would you define the superclasses of a class?

Superclasses of a class is from which the class is dervice from.
Eg.   class man():
         a=10
         
      class child(man):
          b=5
          
Here man is the superclass of the class named child
         
         
         


```python

```
