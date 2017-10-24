1. In Java the most basic way to store data is in a **variable**.
2. A variable is simply a place in the computer's memory that is reserved for us to put our data. To access that space, we need an easy way to refer to it. To do that we give the variable a **name**.
3. We also need to tell the program what **type** of data we would like to put in the space. Java has several basic (_primitive_)
4. The following types all hold a single integer each. an integer is a whole number or what mathematicians call "natural numbers" (e.g. -1, 0, 1, or 2, etc).
 - `byte` - an 8-bit number
 - `short` - a short integer number
 - `int` - an integer number
 - `long` - a large integer number
5. There are two data types that hold numbers with a decimal point, that is what mathematicians call a "real number" (e.g. -1.2345, 0, 1.0 or 3.14159, etc)
 - `float` - a single-precision floating-point number
 - `double` - double-precision floating-point number
6. There is one data type called a `boolean`. This type holds either `true` or `false`.
7. There is one data type called a `char`. This can hold a single character, a letter, such as 'r' or 'T'.
8. To create one of these variables we **declare** it.
9. To declare a variable we type that data type, followed by the name. We need to do this before we can use the variable but once it is done once we don't need to do it again:

```java
int myAge;
```

10. To make use of this variable we can _define_ its value by assigning the value to it. To do this we use the `=` symbol.

```java
myAge = 14;
```

11. It is common, though not necessary, to combine the declaration and definition into a single statement like so:

```java
int myAge = 14;
```