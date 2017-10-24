1. To write some Java code we can use a simple **text editor**, such as Notepad. If you already have an **integrated development environment** \(IDE\) that you would like to use, you can use that also but it is not required. 
2. For our first program we will create a file called `HelloWorld.java`. Open your chosen editor and begin by saving a new blank file with the name `HelloWorld.java`. Be sure that the name is spelled correctly and has the correct case as it is important that it matches. The `.java` part is the** file extension**. Normally files saved in a text editor may be saved with a `.txt` extension so you will need to make sure the extension is definitely changed to `.java`.
3. Add the following code to your file in the text editor. For now, don't worry about what this means, just ensure that the `HelloWorld` part matches the file name exactly.

   ```java
   public class HelloWorld {

   }
   ```

4. Then add the following between the two curly braces. Again, for now don't worry about what the `public static main (String args[])` part means, just note that it, and the curly braces are necessary to make the code work.

   ```java
   public class HelloWorld {
     public static void main(String args[]) {

     }
   }
   ```

5. In between this _second_ set of braces, we can add the code we want to do some work for us, in this case print some text to the terminal, or as it is called in Java, the _console_.

6. Now we can add the code that does the work! Do this with one more line of code:

   ```java
   public class HelloWorld {
     public static void main(String args[]) {
       System.out.println("Hello world!");
     }
   }
   ```

7. This code asks the system to print out a line of text for us. The text we ask it to print out is `Hello world!`.

8. To make this file with our Java code into a program we need to **compile** it. We have a tool in the JRE that will do this for us called `javac`.

9. To use `javac` open a terminal and navigate to the Java file. Then use the following command:

   ```bash
   javac HelloWorld.java
   ```

10. If the command succeeds you will see a new file created in the same location called `HelloWorld.class`.

11. To see this program in action we need to ask the JRE to run it for us. You can do this by using the following command in the terminal. Note that you should not include any extension for the name of the file you want to run but Java will know you mean the file with the `.class` extension.

    ```bash
    java HelloWorld
    ```

12. If everything goes correctly you should see the text we wanted to print out showing in the terminal. Like so:

    ```bash
    java HelloWorld
    Hello world!
    ```

13. Try changing the code so that instead of saying hello to the world it says hello to you using your name. Good luck!



