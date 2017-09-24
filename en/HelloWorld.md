1. To write some Java code we can use a simple **text editor**, such as Notepad. If you already have an **integrated development environment** \(IDE\) that you would like to use, you can use that also but it is not required. 
2. Java is an **object orientated programming** \(OOP\) language, that is the program is constructed out of code constructs we call **objects** where a particular type of object may have some data and some behaviour associated with it. Each object can represent a real world concept, or _thing_, for example a chair.
3. A program that is object orientated is one that creates and uses these objects to achieve the functionality required.
4. We can design each type of object that we want by creating a **class**. A class is like a blueprint or plan for how the program should create that type of object. For example, if we want to create a program for counting chairs we might create a class called `Chair`. In Java we would do that like this:
 ```java
 class Chair {

 }
 ```
5. In between those curly braces (the `{` and `}`) we can add code that contains the data and functionality that we need to represent a chair, such as how many legs it has and the sound it might make when you sit down in it.
6. In Java nearly everything is a class. For our first program we will create a file called `HelloWorld.java`. This means the class in the file should be called the same name. 
7. Open your chosen editor and begin by saving a new blank file with the name `HelloWorld.java`. Be sure that the name is spelled correctly and has the correct case as it is important that it matches the name of the class. The `.java` part is the** file extension**. Normally files saved in a text editor may be saved with a `.txt` extension so you will need to make sure the extension is definitely changed to `.java`.
8. Because our filename is `HelloWorld.java`, our class will be called `HelloWorld`. Add the following code to your file in the text editor. For now, don't worry about what the `public` part means.
 ```java
 public class HelloWorld {

 }
 ```
9. This class is called HelloWorld, we can add code to it to print some text to the terminal, or as it is called in Java, the _console_. 
10. When we add code that performs some specific functionality to an class it is called a **method**. 
11. Every Java program requires exactly one method called `main`. The reason it is called main is historical and you don't really need to worry about why for now, just now that this is how it looks and you should add this between the curly braces that you just added for the class, like below. Again, for now don't worry about what the `public static` and `(String args[])` part mean for now, just note that they, and the curly braces are necessary to make the code work.
 ```java
 public class HelloWorld {
     public static void main(String args[]) {
     
     }
 }
 ```
12. In between this _second_ set of braces, we can add the code we want to do some work for us, in this case print some text to the console.
13. Now the juicy part, adding the code that does this work! We can do this with one more line of code:
 ```java
 public class HelloWorld {
     public static void main(String args[]) {
         System.out.println("Hello world!");
     }
 }
 ```
14. This code asks the system to print out a line of text for us. The text we ask it to print out is `Hello world!`.
15. To make this file with our Java code into it into a program we need to **compile** it. We have a tool in the JRE that will do this for us called `javac`.
16. To use `javac` open a terminal and navigate to the Java file. Then use the following command:
 ```bash
 javac HelloWorld.java
 ```
17. If the command succeeds you will see a new file created in the same location called `HelloWorld.class`.
18. To see this program in action we need to ask the JRE to run it for us. You can do this by using the following command in the terminal. Note that you should not include any extension for the name of the file you want to run but Java will know you mean the file with the `.class` extension.
 ```bash
 java HelloWorld
 ```
19. If everything goes correctly you should see the text we wanted to print out showing in the terminal. Like so:
 ```bash
 java HelloWorld
  Hello world!
 ```
20. Try changing the code so that instead of saying hello to the world it says hello to you using your name. Good luck!



