Class:
    User- defined blueprint or prototype from which objects are created.
    Provides a means of bundling data and functionality together.

Definig a class: 
    class ClassNAme:
        #class definition
    class Bike:
        name = ""
        gear = 0

Objects:
    An object is called an instance of the class 
    Syntax:
        objectName = ClassName()
    bike1 = Bike()

Accessing the Attributes:
    bike1.name = "Bike"
    bike1.gear = 11

Python Constructors:
    __init__ is the constructor function that is called whenever a new object of the class is instantiated.

__init__ 
    Used ito initializes the object's stats.

__del__
    Referred to as the deconstructor method.
    Called after an object's garbage collection occurs, which happens after all references to the item have been destroyed.

__getitem__
    Used for indexing.
    Declared as:
        def __getitem__(self, key):

__setitem__
    Used to assign the values to the indexed values.
    Declared as:
        def __setitem__(self, key, value):

Public and Private Data Members:
    Public Members (generally methods declared in a class) are accessible from outside the class
    The double underscore (__) prefixed to the variable makes it private. It gives a strong suggestion not to touch  it from outside the class.

Built-in Class Attribute:
    .__dict__:
        Gives dictonary containing the classes or attributes
    .__doc__:
        Gives the documentation string if specified, if not specified, it returns None.
    .__name__:
        Returns the name of the class or attribute.
    .__module__:
        Gives the name of the module in which the class is defined.
    .__bases__:
        Used in inheritance to return the base classesin the order of occurrence.