Methods
=======
* Writing Methods
* Calling Methods

Two different things must be done to use methods. First, a method must be written. Second, it must be *called*.

First, what is a method?

**Method** -> The 'action' of a class, or what preforms an operation.

## Writing Methods
 Methods can do two things: preform an operation, and return a type of variable. They can do one, or both.  So, let's take our 'dog' example from earlier. You have a dog, who does three things: he sleeps, eats, and barks. All three of these are methods. However, only one of them will return a variable (barks). 
 
 ```Java
 public class Dog {
     public String food; 
     public static void run() {
         //this method does not return any kind of variable. 
     }
     public static void eat (String food) {
         this.food = food; 
         //this assigns the public variable, assigned just under public class Dog, to the local variable, String food, which is assigned in the method. 
         //It doesn't return anything.
     } 
     public static String bark() {
         return "woof"; 
         //This returns a string.
     }
 }
 ```

Methods are composed of a few different parts. 

First, the **modifier**, public static. We haven't learned about modifiers yet, but we'll address them shortly. 

Second, the **return type**. This is what kind of variable the method will return-- or, if it doesn't return one, then "void." **Void** means that nothing will be returned. 

Next comes the **method name**. This is the part of the method that tells us what to call it. For example, ``bark`` is a method name. 

Third, the **body.** The body of a method is anything that is contained between the two {curly braces}. 

## Running Methods 
Methods can be run in a few different ways. One can either set a variable equal to a result returned by a method, or simply call the method. Both are listed below: 

```Java
String dogSays = dog.bark(); //This sets the string equal to "woof", or what the method bark() returns.
dog.eat("biscuit"); //This, however, sets the type of food the dog eats, in the method eat, to biscuit. 
```

## Extensions 

https://www.w3schools.com/java/java_methods.asp (basics)

https://www.geeksforgeeks.org/methods-in-java/ (in depth)

https://www.tutorialspoint.com/java/java_methods.htm (in depth)