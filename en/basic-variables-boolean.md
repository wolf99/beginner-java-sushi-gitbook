1. A **Boolean** type variable is one that can only be either `true` or `false`.
3. In Java the Boolean type is denoted by the keyword `boolean`.
4. To create a Boolean variable, just as with other type variables, we **declare** it:

   ```java
   boolean isThisASushiCard;
   ```

   Here, the type of the variable comes first, then the **name** of the variable, which is `isThisASushiCard`. The name is followed by a semi-colon \(`;`\) to show that the statement stops here.
5. To make use of this variable we can **assign** a value to it using the equals symbol \(`=`\).

   ```java
   boolean isThisASushiCard;
   isThisASushiCard = true;
   ```

6. It is possible to combine the declaration and assignment into a single statement, called a **definition**, like so:

   ```java
   boolean isThisASushiCard = true;
   ```

10. Add the following code to a new file called `BasicBoolean.java`

    ```java
    public class BasicBoolean{
      public static void main(String[] args){
        boolean isThisASushiCard = true;
        System.out.println("It is " + isThisASushiCard + " that this is a sushi card");
      }
    }
    ```

11. Compile `BasicBoolean.java` and then run `BasicBoolean` to see the output.
12. Try changing the value of the Boolean and the text to make a funny sentence and then save it and compile it and run it again.