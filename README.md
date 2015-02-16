[Eclipse Tutorial](https://github.com/RochesterinNYC/1004-Eclipse-Tutorial)
---
####1004 - Intro to Computer Science and Programming in Java
-------

This is a tutorial on Eclipse, an integrated development environment that you may choose to use in writing and running your Java projects and programs. Written by Hyonjee Joo. Modified by James Wen.

-------

###Table of Contents

- [Terms and Definitions](#terms)
- [Installation](#installation)
- [View Panels](#panels)
- [Creating Projects/Programs](#projects)
- [Running Programs](#run)
- [Importing Files](#import)
- [Submitting Assignments](#submission)
- [Other Notes](#other)
- [More Resources/Documentation](#docs)

-------

<a name="terms"></a>

###Terms and Definitions:

####Eclipse 

– One of the most widely used IDEs for Java and also the IDE that we will be supporting for 1004
- Also allows for installation of plugins that add extra features and support for a large variety of other programming languages 

####IDE (Integrated Development Environment) 

- A software program that provides a visual environment with a variety of useful tools to allow for the writing, running, and testing of code

####Code Editor

– A specialized text editor that usually provides syntax highlighting, auto-complete, auto-formatting, etc.

####Compiler

– A program that transforms source code of one programming language into a different target language (often a language that can be executed directly by computers
- Example: javac ("Java Compiler") transforms Java source code into bytecode

####Debugger 

- A type of program or plugin into IDEs serves as a tool that helps programmers find errors in their code

####GUI (Graphical User Interface) 

– A visual interface that allows a user to interact with computers through graphics and visual elements rather than simple commands and text input/output

------

<a name="Installation"></a>

###Download/Installation:

- Download Eclipse Luna from the website: http://www.eclipse.org/downloads/
- The first link will be the most recent, most common version
- Be sure to download the right version for your operating system (Mac, Linux, Windows; 32-bit or 64-bit)
- To determine whether your system is 32 bit or 64 bit refer to the following instructions/site for Mac and Linux (http://www.howtogeek.com/198615/how-to-check-if-your-linux-system-is-32-bit-or-64-bit/) and the following for Windows (http://support.microsoft.com/kb/827218?wa=wsignin1.0)
- Unzip the downloaded file and open and run the installation program/executable
- For Mac OSes, move the unzipped eclipse directory into the Applications directory and then run the Eclipse executable in that directory to run Eclipse

###Initial Setup:

- Whenever you run Eclipse, you will be asked to select a workspace. This workspace is the directory on your computer where all of the projects you create and programs/code you write will be stored. Check the option to "Use this as the default and do not ask again" to only have to select your workspace on the first run.
- Feel free to explore around with the intro options or select "Workbench" in the top right corner to go to the usual Eclipse interface where you'd write, test, and run your Java programs.

####Some Potential Setup Issues:

Eclipse crashes or closes instantly:
- Installation was not completed properly or in the case of Mac OSes, the Eclipse program is not being run from the unzipped eclipse folder/directory.

No JDK (Java Development Kit):
- Download JDK from http://www.oracle.com/technetwork/java/javase/downloads/index.html
- Follow step by step instructions http://docs.oracle.com/javase/8/docs/technotes/guides/install/install_overview.html

------

<a name="panels"></a>

###View Panels:

The Eclipse interface has many panels that you can close or open and that each provide some functionality, information, or view. You can drag around and move panels anywhere in the interface. A few notable ones:

- Package Explorer = displays your Eclipse imported/integrated projects and allows you to expand, open, and perform operations on the directories and program/code file contents of these projects 
- Console = displays the output from running your Java programs (Ex. output of System.out.println() calls), also displays runtime errors/exceptions
- Javadoc = displays formal Javadoc (a specific style/standard for documenting Java code/programs) for the current class or package 
- Problems = displays syntax or compilation errors that need to be fixed  
- Outline = displays a quick listing of the current project's Java classes and their method names/calling signatures and parameters 

To open any view panels that you've closed or open new view panels, look for the view panels you want to open in (Menu) Window --> Show View --> View Panel you want to open.

------

<a name="projects"></a>

###Creating Projects and Classes:

####Creating a New Project:

- A project should be a single, self-contained collection of one or multiple Java files that work together for some functionality (one project for each assignment). 
- To Create: (Menu) File --> New --> Java Project or Right-click in the Package Explorer view panel --> New --> Java Project
- Name your project accordingly and select Finish.
- Your new project and directory will be created. Each project has a src (stands for source) folder where your code (Java files) will go. 

####Creating a New Java Class/File:

- To Create: (Menu) File --> New --> Java Class (the new Java class will be created for whichever project is currently highlighted/selected in the Package Explorer) or Right-click a Java Project in the Package Explorer --> New --> Java Class
- Give your class an appropriate name in camelCase formatting (ex. HelloWorld, ProcessRunner2, etc.). Keep the default settings. Select Finish.
- Your new Java class and file will be created.

------

<a name="run"></a>

###Running Programs:

Once you have written your program, you can run them. Running the program in Eclipse performs both compilation and execution of the program (ex. like running javac HelloWorld.java and java HelloWorld sequentially).

- To Run: (Menu) Run --> Run or click the green play button in the toolbar
- To run your program with specific command line arguments (ex. want to run command-line equivalent of java CalculateBalance 2000), specify the program arguments in (Menu) Run --> Run Configurations --> Arguments --> Program arguments (fill in arguments, separated by spaces, ex. 2000)

------

<a name="import"></a>

###Importing Files:

Import Courseworks code into your Java Projects:

- Download the Java files from Courseworks. You can save these anywhere (does not have to be saved in your Eclipse workspace directory)
- Right-click on your Java Project in the Package Explorer --> Import --> General --> File System --> Next --> Browse and select the directory that contains the Courseworks Java files 
- Select the specific files you want to import.
- Click Finish and those specified files will be imported and integrated into the selected Project.

------

<a name="submission"></a>

###Submitting Assignments:

Submit your first assignment:

- Open your terminal/command-line or system file navigator (Finder for Linux, Mac or Explorer for Windows)
- Go to your Java Project's src directory:

        PathToYourWorkspace/JavaProjectName/src

- Example (if ~/Programming/Java is your workspace and your Project is called MathCalculator):

        ~/Programming/Java/MathCalculator/src 

- Create a new folder anywhere and copy into it ONLY the .java files from the src directory of your Project
- Compress the folder into a .zip or .tar.gz file.
- Resulting file should be called: uni_hw#.zip (ex. az1234_hw1.zip or az1234_hw1.tar.gz)

------

<a name="other"></a>

###Other Notes:

- No packages (when creating a new class, do not specify a package)
- To autocomplete: Control + Spacebar
- To auto-format your code: Select all files in Package Explorer to be formatted --> right click --> Source --> Format
- Class names should be in upper camelCase (i.e. HelloWorld not helloWorld, hello_world, etc.)
- Put instance variables at the top of the class.
- Indentations should be consistent.

------

<a name="docs"></a>

###More Resources/Documentation:

<a href="http://www.eclipse.org/documentation">Official Eclipse Documentation</a>

<a href="http://marketplace.eclipse.org/">Eclipse Plugins</a>

<a href="http://www.vogella.com/tutorials/Eclipse/article.html">Vogella Eclipse Tutorial (lots of screenshots)</a>
