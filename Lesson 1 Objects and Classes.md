Java Structure 
========
* Objects
* Classes
* Inheritance
* Packages and Libraries

**Objects** -> A thing with a state and a behavior. An example is a dog with red fur, that is barking. The fur color is a state, and the barking is a behavior.

**Class** -> A class is the 'blueprint' that defines the behavior/state of an object. 

**Inheritance** -> The way one class takes on the properties (methods/fields) of another class.

**Package** -> A way of grouping related classes. 

**Libraries** -> Previously written code that can be called upon when writing code. 

## Objects
Software objects are very similar to real-life objects. Just like a dog has states and behaviors, objects also have states and behaviors. Software states are stored in things called 'fields' or 'variables' and software behaviors are stored in 'methods'. 

Methods are composed of things that objects can *do*, while variables and fields are composed of *characteristics* of objects. 

## Classes 
Classes are the blueprints that create objects. While an individual dog may have different fur colors, it will always have *fur*. As such, a dog may contain fields or variables like `furColor`, `breed`, and `age`. It may contain methods such as `bark`, `sleep`, and `run`.
```Java
public class Dog {
    String furColor; 
    String breed; 
    int age; 

    public static void bark() {
    }

    public static void sleep() {
    }

    public static void run() {
    }

} 
```

## Inheritance 
Inheritance is the process that allows one class to 'inherit' the properties of another. If class B inherits class A, then class B now has the methods and fields of class A. 

**Superclass** -> The class being inherited. (Class A). 

**Subclass** -> The class inheriting. (Class B).

Say we have two classess: animal and dog. Class animal has the properties ``legs`` and ``eyes``, and the methods ``walk`` and ``eat``. ``Public class Dog`` inherits ``public class Animal``. Now, ``class Dog`` has access to the variables  ``legs`` and ``eyes`` and the methods ``walk`` and ``eat.`` Inheritance is signalled by the word ``extends``. 


```Java
public class Animal {
    int legs; 
    int eyes; 
    
    public void walk() {
    } 
    public void eat() {
    }
}

public class Dog extends Animal { //Animal is "inherited" here 
    String furColor; 
    String breed; 
    int age; 
    public static void bark() {
    }

    public static void main (String[] args) { //This is where methods are called. 
        Dog fido = new Dog(); //This creates a new Dog object, called Fido
        fido.walk(); //This calls the Animal method, walk, on Fido
    }

} 
```

## Packages and Libraries

Packages are ways to group different classes (files) together. They relate the classes to each other. Libraries, for example, are packages. Packages are used to divide code into easier to read sections. 

Packages can be imported, as seen below: 
```Java
import java.util.Math;
```
The package is ``java.util``, while ``Math`` is the class you're importing. After importing the ``java.util.Math`` class, you can now use all of the methods in the ``Math`` class. 

## Extensions 
Further resources: 

https://www.w3schools.com/java/java_classes.asp (Classes: basics)

https://www.tutorialspoint.com/java/java_object_classes.htm (Classes: in depth)

https://www.w3schools.com/java/java_inheritance.asp (Inheritance: basics) 

https://www.tutorialspoint.com/java/java_inheritance.htm (Inheritance: in depth)

http://tutorials.jenkov.com/java/packages.html (Packages: in depth)

