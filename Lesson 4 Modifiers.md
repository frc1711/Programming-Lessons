Modifiers
===
* Access Modifiers 
* Non-access Modifiers 

**Access Modifiers** -> Sets the 'security' level for a class, variable, or method. This is what determines what can 'see' the class, variable, or method. 

**Non-access Modifiers** -> Define other functionalities beyond access, such as editing rights. 

## Access Modifiers

The access modifier for a class takes precedence over the access modifiers for the variables and methods inside of it. If a class is defined as 'default,' a 'public' variable inside of it cannot be accessed outside of the package. 

Additionally, classes cannot be assigned 'protected' or 'private' modifiers. 

**Public:** Can be accessed by all code, regardless of where the code is located

**Private:** Can only be accessed by code inside the same class. Private can't be used for a class itself, only methods and variables. This is because if a class was marked 'private' and would be essentially useless.

**Default**: This class modifier is declared by not specifying a class modifier. The default class modifier makes it so that all classes in the package can access the class, but only classes in the package. 

**Protected**: The protected access modifier is the same as the default access modifer, with one exception: subclasses can access the variables and methods inside of it, even if the superclass is not part of the package. 

In FIRST robotics, the most commonly used access modifiers are public and private. However, it is important to know *all* of the access modifiers to fully understand the code you are writing and reading. 

## Non-access Modifiers

Non-access modifiers can define several aspects of a class, method, and/or variable. However, the only non-access modifiers you can use on classes are ``final`` and ``abstract``. All of the other non-access modifiers can only be used on methods and attributes. 

**Final:** 

-Two different meanings, dependent upon where it's used. 

-Classes with the final modifier cannot be inherited.

-Attributes and methods cannot be overwritten or changed. 

**Abstract:** 

-Two different meanings, dependent upon where it's used. 

-Only methods and classes  

-Abstract classes cannot be used to create objects. However, they can be inherited as superclasses. 

-Abstract methods do not have to have a body. For example, an abstract method can look like ``abstract void walk();``. Abstract methods are defined by the subclass they're inherited by. 

**Static:** Attributes and methods belong to the class, not the method. 

While there are other kinds of non-access modifiers, the above are (generally) the only kind relevant in FIRST robotics. See the extensions if you'd like to learn more about the other kinds. 

## Extensions
https://www.javatpoint.com/access-modifiers (basic)

https://www.w3schools.com/java/java_modifiers.asp (basic) 

http://tutorials.jenkov.com/java/access-modifiers.html#class-access-modifiers (in depth)

https://beginnersbook.com/2013/05/java-access-modifiers/ (in depth)