### Python Classes and Basic OOP Tutorial 

# This Repo was intended as notes for me but you are welcome to use this as a basic tutorial!

* What is OOP?
    * A way to organize your code, also known as paradigm.
    * Develop large Software or even small making them easier.
    * You can associate real world objects and replationships in your code
    * NOT ALL Programs should be written in OOP or need to be 
    * Python allows you to use OOP or not use OOP or mix both paradigm.

* Objects:
    * a "Thing" in your program
    * example a PERSON
        * Can Walk, Talk or Run
        * Can have a named
        * You can define your own classes

* Classes are used to create objects:
    * you can create many, unique objects from a single class
    * Classes define the type.
    * When you create and object from a class that is know as "instantianting".

* Classes have "Properties" and "Behaviors".
    * Example: 
    * person class:
        - properties
            - name
            - height
         - behaviors:
           - run 
           - talk 
           - walk

## Example code Class and file where I instantiate different objects from the same class
    * in the class example I create a "Dog" class
    * in the file I import the class and instantiate different objects (2 different dogs) fromt the class
    * In Python you can easily buld classes.

```
class Dog:

    def __init__(self, name, age):
        self.name = name
        self.age = age
```



