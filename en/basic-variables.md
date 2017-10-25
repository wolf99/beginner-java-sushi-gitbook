1. In Java the most basic way to store data is in a **variable**.
2. A variable is simply a place in the computer's memory that we reserve to hold data for us. To access that space, we need an easy way to refer to it. To do that we give the variable a **name**.
3. We also need to tell the program what **type** of data we would like to put in the space. Java has several basic \(_primitive_\) data types. The easiest to begin with is an **integer**.
4. An integer is a whole number, or what mathematicians call a "natural number". That is, a positive or negative number without a decimal point \(e.g. -3 or 0 or 1 or 16, etc\).
5. In Java the integer type is denoted by the keyword `int`.
6. To create a variable we **declare** it.
7. To declare a variable we type the data type \(in this case `int`\), followed by the name. We need to do this before we can use the variable but once it is done once we don't need to do it again:

   ```java
   int myAge;
   ```

   Here, the type of the variable comes first, then the name of the variable, which is `myAge`. The is followed by a semi-colon \(`;`\) to show that the statement stops here.

8. To make use of this variable we can assign a value to it. To do this we use the equals symbol \(`=`\).

   ```java
   myAge = 14;
   ```

9. It is common, though not necessary, to combine the declaration and assignment into a single statement, called a _definition_, like so:

   ```java
   int myAge = 14;
   ```

10. Add the following code to a new file called `MyAgeInt.java`

    ```java
    public class MyAgeInt{
      public static void main(String[] args){
        int myAge = 12;
        System.out.println("My age is: " + myAge);
      }
    }
    ```

11. Compile `MyAgeInt.java` and then run `MyAgeInt` to see the output.

12. Change the `myAge` variable to hold your real age and then save it and compile it and run it again.



