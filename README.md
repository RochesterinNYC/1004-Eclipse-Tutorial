[Eclipse Tutorial](https://github.com/RochesterinNYC/1004-Eclipse-Tutorial)
---
####1004 - Intro to Computer Science and Programming in Java
-------

This is a tutorial on Eclipse, an integrated development environment that you may choose to use in writing and running your Java projects and programs.

-------

###Table of Contents

- [Terms/Definitions](#terms)
- [Installation](#installation)
- [CUNIX](#cunix)
- [Projects](#projects)
- [Running Programs(#run)
- [Importing Files](#import)
- [Submitting Assignments](#submission)
- [Other Notes](#other)
- [More Resources/Documentation](#docs)

-------

<a name="terms"></a>

###Term Definitions:

####Eclipse 
– one of the most widely used IDEs for Java, and also the IDE that we will be supporting for this course

####IDE (Integrated Development Environment) 
- a computer program that helps us code by providing a friendly environment and useful programming tools

####Code Editor
– editor with syntax highlighting, autocomplete, formatting

####Compiler
– turns source code (code that humans can write and understand) into executables (code that computers can run), e.g. javac (“Java Compiler”)

####Debugger 
– tools that helps programmers find errors in their code

####GUI (Graphical User Interface) 
– a way of interacting with computers that involves graphics; anything beyond command line interface

------

<a name="Installation"></a>

###Download:

- Download Eclipse Luna from the website: http://www.eclipse.org/downloads/
- The first link will be the most recent, most common version
- Be sure to download the right version for your operating system (Mac, Linux, Windows; 32-bit or 64-bit)
- Unzip downloaded file and open/run

###Some Potential Issues:
- No JDK (Java Development Kit)
- Download JDK from http://www.oracle.com/technetwork/java/javase/downloads/index.html
- Follow step by step instructions http://docs.oracle.com/javase/8/docs/technotes/guides/install/install_overview.html

------

<a name="projects"></a>

###Creating Projects and Classes:

Write your first “Hello, World!” program:

- Start eclipse
- Pick a folder for your Eclipse workspace. This is where Eclipse stores and organizes your code on your file system.
- Make sure you're on the Java perspective. 
- Window → Open perspective → Java
- Create a new project. A project should be a single, self-contained program (one project for each assignment). Your project has a src folder where you will put your code and your build dependencies, which in this case is just the JDK.
- File → New → Java Project OR Right-click Package Explorer → New → Java Project
- Create a new Java class.
- File → New → Java Class OR Right-click a Java Project → New → Java Class
- Give your class a name (HelloWorld) – should be in upper camel case. Keep the default settings.
- Start writing!

------

<a name="run"></a>

###Running Programs:

Once you have written your program, run the program. Running the program compiles AND executes the program (e.g. javac HelloWorld.java && java HelloWorld in one step).

- Run → Run OR Click the green play button on the top toolbar

------

<a name="import"></a>

###Importing Files:

Import Courseworks code into your Java Projects:

1.  Download the code from Coursework. You can save it anywhere – it does not have to  be saved in your Eclipse workspace directory.
2.  Right-click on the src folder of your Java Project → Import → General → File System → Top 'From directory' Browse 
3.  Select the directory where you saved the source code
4.  Select the files you want to import.
5.  Click finish

------

<a name="submission"></a>

###Submitting Assignments:

Submit your first assignment:

1.  Open your terminal or Finder (Linux, Mac) or Window's Explorer (Windows)
2.  Go to your Java Project's src directory
3.  <PathToYourWorkspace>/<JavaProjectName>/src
4.  create new folder with ONLY .java files from src directory
5.  Compress folder into .zip or .tar.gz file
6.  Folder should be <uni>_hw#.zip (i.e. az1234_hw1.zip)

------

<a name="other"></a>

###Other Notes:

- No packages – when creating a new class DO NOT specify a package
- Some tips
- Control + space = autocomplete
- After you finish writing your code:
- Select All → Source → Format
- Style guidelines
- Class names should be in upper camel case (i.e. HelloWorld not helloWorld, hello_world, etc.)
- Put instance variables at the top of the class
- Indentations should be consistent


------

<a name="docs"></a>

###More Resources/Documentation: