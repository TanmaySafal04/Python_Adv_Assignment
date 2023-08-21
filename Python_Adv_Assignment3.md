1. What is the concept of an abstract superclass?

2. What happens when a class statement&#39;s top level contains a basic assignment statement?

3. Why does a class need to manually call a superclass&#39;s __init__ method?

4. How can you augment, instead of completely replacing, an inherited method?

5. How is the local scope of a class different from that of a function?

# Solution

#1 What is the concept of an abstract superclass?

An abstract class can be considered as a blueprint for other classes. It allows you to create a set of methods that must be created within any child classes built from the abstract class. A class which contains one or more abstract methods is called an abstract class.

#2 What happens when a class statement's top level contains a basic assignment statement?

When a class statement's top level contains a basic assignment statement, that assignment statement is executed when the class is defined, and it becomes a class attribute.

#3 Why does a class need to manually call a superclass's init method?

Manually calling a superclass's __init__ method in a subclass allows you to build upon the existing initialization logic, avoid code duplication, and customize the behavior as needed.

#4 How can you augment, instead of completely replacing, an inherited method?

To augment, or extend, an inherited method without completely replacing it in a subclass, you can follow these steps:

Call the Superclass Method: Inside the subclass, call the superclass's method you want to extend. This ensures that the original behavior defined in the superclass is executed.

Add Additional Functionality: After calling the superclass method, you can add your own additional functionality specific to the subclass

#5 How is the local scope of a class different from that of a function?

When you define variables within a class (outside of any methods), these variables become class attributes and are accessible throughout the class, including its methods.

Variables defined within a function are local to that function's scope. They can only be accessed within the function and not outside of it.


```python

```
