Primitive Data Types / Variables
=====
* Numbers
    * Integer Types
    * Floating Types
* Other 
    * Characters
    * Strings
    * Boolean

**Integer Types** -> Store whole numbers (no decimals). These can be positive or negative. 

**Floating Types** -> Store numbers with a fractional part (decimals). 

**Characters** -> Used to store single characters. 

**Strings** -> Stores a sequence of characters. A string of text longer than one character. 

**Boolean** -> Stores a ``true`` or ``false`` variable. 
## Numbers 
### Integer Types 
Integer types are positive or negative whole numbers (without decimals). 

#### Byte
-Bytes store whole numbers from -128 to 127.

-They take up the least memory space (a single byte). 

-The default value of a byte is 0. 

-Ex: ``byte example = 100;``

#### Short 
-Shorts store whole numbers from -32,768 to 32,767

-They take up the second least memory space (two bytes)

-The default value of a short is 0. 

-Ex: ``short example = -300;``

#### Int
-The most commonly used integer data type. You should be using these in most of the code you write, unless you have a specific reason to want to save space. 

-Integers store values from -2,147,483,648 to 2,147,483,647. 

-Every integer takes up 4 bytes of space. 

-Ex: ``int example = 20;``

#### Long 
-Stores values from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807. 

-Used only when a number larger than an integer is needed. 

-Every long takes up 8 bytes of space. 

-Values should end with an L.

-Ex: ``long example = 100000L;``.

### Floating Types
Floating types are positive or negative numbers with a fractional part. 

#### Float 
-All values should end with an f. 

-Default value is 0.0f. 

-Takes up 4 bytes of space.

-Ex: ``float example = 1.0f;`` 

#### Double 
-The most commonly used floating data type. You should be using these in most of the code you write, unless you have a specific reason for using another. 

-Takes up 8 bytes of space.

-Ex: ``double example = 3.05;``

## Other Data Types
#### Boolean 
-Can only take two values: ``true`` and ``false``

-Ex: ``boolean example = true;`` 

-Takes up 1 bit of space

-Can be replaced with a boolean expression. A boolean expression is something that evaluates to either ``true`` or ``false``. 

-Ex: ``7 < 8`` evaluates to ``true``.

#### Character
-Used to store a single alphanumeric character. 

-Must be surrounded by single quotes ``'``. 

-ASCII characters can also be printed out. 

-Ex: ``char a = 65;`` prints out to ``A``. 

-Takes up 2 bytes of space.

#### String 
-Used to store a sequence of characters. Composed of text.

-Must be surrounded by double quotes. 

-Called the "special ninth type" in Java because it is used so often.

-Actually a non-primitive data type (functions as an object) but is often listed as primitive

-String is a type of object, not a primitive data-type. 

-Ex:  ``String example = "example";``
