## FactoryMethod design pattern

Factory method is a creational design pattern which solves the problem of creating product objects without specifying their concrete classes.

Factory Method defines a method, which should be used for creating objects instead of direct constructor call (new operator). 

Subclasses can override this method to change the class of objects that will be created.

Identification: Factory methods can be recognized by creation methods, which create objects from concrete classes, 

but return them as objects of abstract type or interface.
