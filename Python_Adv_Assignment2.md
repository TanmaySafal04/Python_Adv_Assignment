Q1. What is the relationship between classes and modules?

Q2. How do you make instances and classes?

Q3. Where and how should be class attributes created?

Q4. Where and how are instance attributes created?

Q5. What does the term &quot;self&quot; in a Python class mean?

Q6. How does a Python class handle operator overloading?

Q7. When do you consider allowing operator overloading of your classes?

Q8. What is the most popular form of operator overloading?

Q9. What are the two most important concepts to grasp in order to comprehend Python OOP code?

# Answers

#1 What is the relationship between classes and modules?

Modules are built in functionalities containing classes which have methods which perfom a specific function. We need not create such functionality again and again and can directly import and use them in our code.

#2 How do you make instances and classes?

We create classes using the class keyword and it's instance by assigning to a variable as if it's a method.

Eg. class abc   ------> #class created
       pass
       
    instance=abc()

#3 Where and how should be class attributes created?

Class attributes should be within the class body after the declaration of class so that it can be accessed by the instances of that class.

#4 Where and how are instance attributes created?

Instance attributes are defined in the constructor using the self keyword inside the class.

#5 What does the term "self" in a Python class mean?

"self" keyword represents instance of the class that is used to access class attributes and methods.

#6 How does a Python class handle operator overloading?

There are overriding methods that are defined in python to handle operator overloading. Eg. for '+' there's a method __add__().
We use this to handle operator overloading.

#7  When do you consider allowing operator overloading of your classes?

Operator overloading it simpler to write code, especially for complex data types. Allows for code reuse by implementing one operator method and using it for other operators.


 #8 What is the most popular form of operator overloading?
 
 '+' operator overloading

#9 What are the two most important concepts to grasp in order to comprehend Python OOP code?

Inheritance and Polymorphism  are the two most important concepts to grasp in order to comprehend Python OOP code


```python

```
