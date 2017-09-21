1. Java is platform independent. This means that it will run on nearly any operating system. Whether your computer runs Windows, Linux, Mac OS, it's all the same to Java! The reason it can run on any operating system is because of the **Java Virtual Machine**. The Virtual Machine is a programme that processes all your Java code correctly. So you need to install this programme \(Virtual Machine\) before you can run any Java code.
2. Java is owned by a company called Oracle, so you need to head over to Oracle's website to get the Java Virtual Machine, also known as the **Java Runtime Environment** \(**JRE**\). Try this page first: [http://java.com/en/download/index.jsp](http://java.com/en/download/index.jsp).
3. You can check to see if you already have the JRE on your computer by clicking the link "Do I have Java?". You'll find this link under the big Download button at the top of the page. When you click the link, your computer will be scanned for the JRE. You will then be told whether you have it or not. If not, you'll be given the opportunity to download and install it.
4. An alternative way to check if you already have the JRE is to open a **command prompt** or **terminal** and type in the command: 
   ```bash
   java -version
   ```

   If you have java installed the command will display the current java version \(_check yours is up to date_\), if you do not have it installed it will likely tell you that the command is not recognised.
5. To select the installer yourself head over to this page: [http://www.oracle.com/technetwork/java/javase/downloads/index.html](http://www.oracle.com/technetwork/java/javase/downloads/index.html).
6. After downloading and installing, you may need to restart you computer. When you do, you will have the Java Virtual Machine!
7. At this stage, you can **run** Java programs but you still can't **write** any programs. To write Java code you need something called a **Software Development Kit**. Java's Software Development Kit \(**JDK**\) contains the tools you will need to change your Java code from plain old text into a program. The JDK we will be using is for **Java SE** \(SE stands for _Standard Edition_\)
8. Again, you can check if the JDK is already installed on your computer by opening a command prompt or terminal and typing in the command (note the extra 'c'!):
   ```bash
   javac -version
   ```
9. The JDK can currently be downloaded from the same link: [http://java.com/en/download/index.jsp](http://java.com/en/download/index.jsp).
10. After downloading and installing, you may need to restart you computer again. When you do, you will have the Java Development Kit!
11. One final step you will need to o to make using java easier is to add the install location of the JDK tools to your system's _Path_ **environment variable**. This is done differently on different systems so ask a mentor or do a web-search to find how to do this. On Microsoft Windows systems the location you add should look like `C:\Program Files\Java\jdk1.8.0\bin`, on Linux `/usr/lib/jvm`.




