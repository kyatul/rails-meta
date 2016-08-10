Reflection is especially useful when you are interactively examining an unfamiliar object of class structure.

Methods like attr_reader uses metaprogrammingto define custom methods.

Object#class => method to get the class of an object as a Class object.
Class#superclass => to get the parent Class of a Class object.

BasicObject is the parent class of all classes (including Objects), and superclass method called on it will return nil.

A class can have only one superclass, but it may contain many ancestors.

Module#ancestors => contains the entire inheritance hierarchy (including the class itself), any modules the class includes.

Object#methods => returns an array containing the names of object's public methods.

likewise, Object#methods => returns object's singleton methods.

To see whether a class defines a certain instance method, call method_defined? on the class or respond_to? on an instance of the class.
