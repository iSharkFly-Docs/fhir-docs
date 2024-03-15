# Eclipse Install

## The First Eclipse Project

The steps how to get 1st Eclipse project create and run.

### Launch Eclipse

1. Start Eclipse by running "eclipse.exe" in the Eclipse installed directory.
2. Choose an appropriate directory for your workspace (i.e., where you would like to save your files).
3. If the "Welcome" screen shows up, close it by clicking the "close" button.

### Create a new Java Project

For each Java application, you need to create a project to keep all the source files, classes and relevant resources.

To create a new Java project:

1. Choose "File" menu ⇒ "New" ⇒ "Java project".
2. The "New Java Project" dialog pops up.
   a. In the "Project name" field, enter "FirstProject".
   b. Check "Use default location".
   c. In the "JRE" box, select "Use default JRE (currently 'JDK1.x')". But check the JDK version, you should be using
   JDK 1.5 and above.
   d. Click "Finish".

### Write a Hello-world Java Program

1. In the "Package Explorer" (left panel) ⇒ Right-click on "FirstProject" (or use the "File" menu) ⇒ New ⇒ Class.
2. The "New Java Class" dialog pops up.
   a. In "Name" field, enter "Hello".
   b. In "package" field, delete the content if it is not empty.
   c. Check "public static void main(String[] args)" box.
   d. Click "Finish".
3. The source file "Hello.java" opens on the editor panel. Enter the following codes:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }

}
```

