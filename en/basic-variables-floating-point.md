1. Just as we can have data types for whole numbers, we can have data **types** for numbers with a decimal, or fractional, part. This is what mathematicians call a "real number". That is, a positive or negative number with a decimal point \(e.g. -3.25 or 0.777 or 1 or 16.365, etc\).
2. In Java (and lots of other programming languages) this is called a **floating-point** number - because the decimal point can "float" around, that is, we can move it where we want it to be.
3. In Java the floating-point type is denoted by the keyword `float` (note that Java has another real number type, `double`, but we won't worry about that yet).
4. To create a floating-point variable, just as with other type variables, we **declare** it:

   ```java
   float myHeight;
   ```

   Here, the type of the variable comes first, then the **name** of the variable, which is `myHeight`. The name is followed by a semi-colon \(`;`\) to show that the statement stops here.
5. To make use of this variable we can **assign** a value to it using the equals symbol \(`=`\).

   ```java
   float myHeight;
   myHeight = 1.5;
   ```

6. It is possible to combine the declaration and assignment into a single statement, called a **definition**, like so:

   ```java
   int myHeight = 1.5;
   ```

10. Add the following code to a new file called `FirstFloat.java`

    ```java
    public class FirstFloat{
      public static void main(String[] args){
        int myHeight = 2.3;
        System.out.println("My height is " + myHeight + " meters");
      }
    }
    ```

11. Compile `FirstFloat.java` and then run `FirstFloat` to see the output.
12. Change the `MyHeight` variable to hold your real height in meters and then save it and compile it and run it again.