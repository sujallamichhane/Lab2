# CSCI 201 FALL 2022
Lab 1 Starter Code

Welcome to GitHub and your first CS201 Lab!

### Learning Goals:
- print to the Standard Output (the screen!)
- allow input from the user through the Standard Input (the keyboard!)


### Creating an IntelliJ Project

First we need to create an IntelliJ project in a well-named, easy to locate folder.

1) If you're using a Lab Workstation, navigate to the H:\ Drive and create a folder called `cs201`.  If you're using your own device, place a folder called `cs201` wherever you can reliably find it. I recommend `Documents\classes`
2) Open IntelliJ. On Lab Workstations, this can be done by navigating to the Start Menu and finding IntelliJ in the JetBrain folder. If you are using a Windows machine of your own, the process is the same. If you are using a Mac, you'll need to find IntelliJ in the Apps location.
3) IntelliJ will open a dialog box the first time you open it. Select "Create a New Project" and click Next. 
4) You can select the Project SDK, you should choose JDK Version 16.0.2.
5) Ensure both Groovy and Kotlin/JVM are NOT selected.
6) Ensure "Create Project from Template" is NOT selected.
7) Set the Project Name to `Lab1`. Set the Project location to `H:\cs201\Lab1` or `[Location on your device]\cs201\Lab1` and click Finish. It will give you a "Directory does not exist" Dialogue. Click Ok to create directory.

## Lab 1 Part 1

### Creating a .java file

Program are written in .java files and compiled into .class files.
1) Click the arrow next to the Lab1 folder in the Project Viewer Pane. This will expand the project folder.
2) Write click on the `src` folder and navigate to `New`. Click `Java Class`. When prompted for a name, name the class `Lab1_1`.

The Text Editor Pane will now contain a page with the following:

```
public class Lab1_1{
}
```

Inside of that class is where you will place the `main` method of your program. That program, when compiled, should print the following:

```
Welcome to CSCI 201!
This is (maybe!) my first Java program!
I'm a "programmer"!
   J    A    V     V    A
   J   A A    V   V    A A
J  J  AAAAA    V V    AAAAA
 JJ  A     A    V    A     A
```

Try printing **exactly** that by calling `print` or `println` only once, and try to print it exactly that way calling `print` or `println` 3 times.

You can compile and run your program in IntelliJ by selecting `Run > Run` from the header, pressing the green "Play Button" next to the `main` method, or pressing `Shift+F10`.

## Lab 1 Part 2

Now, we need want to create a Java program which asks the user for some information and uses that information later.

1) Write click on the `src` folder and navigate to `New`. Click `Java Class`. When prompted for a name, name the class `Lab1_2`.
2) Note, you know have two .java files in the SAME src folder. These can be organized into what a known as `Packages`. But we'll discuss that more later.

Inside the `Lab1_2` class, create a `main` method which does the follow:

It should prompt the user for their name and age:

```
Enter your name:
Enter your age:
```

You should enter your name and age in the appropriate location and store them as `String` variables. Then, the program should print:

```
Hi [name you entered]! Welcome to CSCI 201!
You are [age you entered] years old!
```

### Submitting the project

When you're done, you can upload your files to this Repo and commit the changes. 

1) Click `Add files ` at the top right of the Repo page.

There are two options:

A) Click "Add Files" to create new Java files in the repo manually. Create new files with name `Lab1_1.java` and `Lab1_2.java` You can re-type or copy paste your code into those files.

B) Click "Upload Files" to just upload the .java files you already created. Navigate to the `src` folder on your computer and upload `Lab1_1.java` and `Lab1_2.java`.

2) Once you've created the file you want, or uploaded them, navigate to the bottom of the Page and hit "Commit changes". Ensure "Commit directly to the `main` branch." is selected. You'll need to "Commit changes" once for each file you "Create" in GitHub, but can upload multiple files before a single Commit. 


