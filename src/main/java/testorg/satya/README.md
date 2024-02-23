# Full Stack Java Course

This is a comprehensive course on Full Stack Java development.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Course Content](#course-content)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This course covers Full Stack Java development, using Java for backend development and various front-end technologies. The course also includes working with databases and deploying your applications.

## Prerequisites

- Basic knowledge of programming concepts
- Familiarity with Java
- An IDE such as IntelliJ IDEA

## Installation

1. Install Java Development Kit (JDK)
2. Install IntelliJ IDEA
3. Clone this repository

## Course Content

1. Introduction to Java
2. Object-Oriented Programming in Java
3. Data Structures in Java
4. Java Servlets
5. Java Server Pages (JSP)
6. Spring Framework
7. Hibernate
8. RESTful Web Services
9. Microservices in Java
10. Front-end Technologies (HTML, CSS, JavaScript)
11. Working with Databases
12. Deploying Java Applications

## Contributing

Contributions are welcome. Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute.

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.

# Install Java Development Kit (JDK)

Follow these steps to install the Java Development Kit (JDK):

1. **Download the JDK**: Visit the [Oracle website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) and download the appropriate JDK for your operating system.

2. **Run the installer**: Once the download is complete, run the installer and follow the instructions. The installer will guide you through the installation process.

3. **Set the JAVA_HOME environment variable**: After the installation is complete, you need to set the JAVA_HOME environment variable to point to the installation directory. This step varies depending on your operating system.

   For Windows:

    - Search for 'Environment Variables' in the Windows search bar and select 'Edit the system environment variables'.
    - In the System Properties window that appears, click on 'Environment Variables'.
    - In the Environment Variables window, click on 'New' under the 'System variables' section.
    - In the New System Variable window, enter 'JAVA_HOME' in the 'Variable name' field and the path to your JDK installation in the 'Variable value' field. Click 'OK' to close the window.
    - In the Environment Variables window, scroll down to the 'Path' variable under 'System variables', select it, and click 'Edit'.
    - In the Edit Environment Variable window, click 'New' and add '%JAVA_HOME%\\bin'. Click 'OK' to close all windows.

4. **Verify the installation**: Open a new command prompt and type 'java -version'. If the JDK is correctly installed, you should see output indicating the version of the JDK.

Please note that the exact steps may vary depending on your operating system and the version of the JDK you are installing. Always refer to the official installation instructions for the most accurate information.

# Install IntelliJ IDEA

Follow these steps to install IntelliJ IDEA:

1. **Download IntelliJ IDEA**: Visit the [JetBrains website](https://www.jetbrains.com/idea/download/) and download the appropriate version of IntelliJ IDEA for your operating system. There are two versions available: Community (free) and Ultimate (paid, with a free trial available).

2. **Run the installer**: Once the download is complete, run the installer and follow the instructions. The installer will guide you through the installation process.

3. **Configure IntelliJ IDEA**: After the installation is complete, you can run IntelliJ IDEA and go through the initial configuration process. This includes selecting a UI theme, creating a desktop shortcut, downloading and installing additional plugins, and setting up the development environment.

4. **Verify the installation**: Open IntelliJ IDEA. If it's correctly installed, you should see the welcome screen, which allows you to create a new project, open an existing project, or check out an existing project from a version control system.

Please note that the exact steps may vary depending on your operating system and the version of IntelliJ IDEA you are installing. Always refer to the official installation instructions for the most accurate information.

To create a Maven project in IntelliJ IDEA and verify a JAR file, you can follow these steps:

# Creating a Maven Project in IntelliJ IDEA
1. Open IntelliJ IDEA.
2. Click on `File` in the menu, then select `New` > `Project`.
3. In the New Project window, select `Maven` from the options on the left.
4. Make sure the `Create from archetype` checkbox is unchecked (unless you want to create a project from an archetype).
5. Click `Next`.
6. On the next page, provide your `GroupId` (usually your company or personal website, e.g., `com.mycompany`), `ArtifactId` (the name of your project, e.g., `myproject`), and `Version` (usually starts with `1.0-SNAPSHOT`).
7. Click `Next`.
8. Choose a project location in the `Project location` field.
9. Click `Finish`.

IntelliJ IDEA will create a new Maven project with a basic directory structure and a `pom.xml` file. The `pom.xml` file is the most important file in a Maven project. It contains information about the project and configuration details used by Maven to build the project.

## Verifying a JAR File

To verify a JAR file, you can use the `jarsigner` tool that comes with the JDK. Here are the steps:

1. Open a terminal.
2. Navigate to the directory containing the JAR file you want to verify.
3. Run the following command: `jarsigner -verify my-file.jar`

Replace `my-file.jar` with the name of your JAR file. If the JAR file is verified, you will see a message saying `jar verified.` If the JAR file is not verified, you will see a message detailing why the verification failed.

Please note that you need to have the JDK installed and the `jarsigner` tool needs to be in your system's PATH to use this command.

# In this Java course, we will Use maven as a built tool. how to setup maven in your intellij IDEA and how to create a maven project.
to see these step-by-step guide please visit this link: https://studyeasy.org/java/intellij-maven-tutorial-creating-a-helloworld-java-program-in-10-easy-steps/


# 1.Introduction to Java
   Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.

Here are some key features of Java:

1. **Object-Oriented**: Everything in Java is an Object. Java can be easily extended since it is based on the Object model.

2. **Platform Independent**: Unlike other programming languages such as C, C++ etc which are compiled into platform specific machines. Java is guaranteed to be write-once, run-anywhere language. On compilation, Java program is compiled into bytecode. This bytecode is platform independent and can be run on any machine, plus this bytecode format also provides security. Any machine with Java Runtime Environment can run Java Programs.

3. **Simple**: Java is designed to be easy to learn. If you understand the basic concept of OOP, Java would be easy to master.

4. **Secure**: With Java's secure feature, it enables to develop virus-free, tamper-free systems. Authentication techniques are based on public-key encryption.

5. **Architecture-neutral**: Java compiler generates an architecture-neutral object file format, which makes the compiled code executable on many processors, with the presence of Java runtime system.

6. **Portable**: Being architecture-neutral and having no implementation dependent aspects of the specification makes Java portable.

7. **Robust**: Java makes an effort to eliminate error-prone situations by emphasizing mainly on compile time error checking and runtime checking.

8. **Multithreaded**: With Java's multithreaded feature, it is possible to write programs that can perform many tasks simultaneously.

9. **Interpreted**: Java byte code is translated on the fly to native machine instructions and is not stored anywhere. The development process is more rapid and analytical since the linking is an incremental and light-weight process.

10. **High Performance**: With the use of Just-In-Time compilers, Java enables high performance.

11. **Distributed**: Java is designed for the distributed environment of the internet.

12. **Dynamic**: Java is considered to be more dynamic than C or C++ since it is designed to adapt to an evolving environment. Java programs can carry an extensive amount of run-time information that can be used to verify and resolve accesses to objects at run-time.

Java is used in a wide variety of computing platforms from embedded devices and mobile phones to enterprise servers and supercomputers. Java applets, which are less common than standalone Java applications, were commonly run in secure, sandboxes environments to provide many features of native applications through being embedded in HTML pages.

# Variables in Java 
In Java, a variable is a container that holds values that are used in a Java program. Every variable is assigned a data type which designates the type and amount of values it can hold.

Here are the types of variables you used in your code:

1. `int`: This is a data type that can hold whole numbers, positive or negative, without decimals, of at least -2,147,483,648 and at most 2,147,483,647.

   Example: `int myNum = 5;`

2. `float`: This is a data type that can hold floating point numbers (i.e., numbers with a decimal point). It can hold positive or negative numbers, with decimals, of at least 1.4e-45 and at most 3.4e+38.

   Example: `float myFloatNum = 5.99f;`

3. `char`: This is a data type that can hold a single character/letter or ASCII values.

   Example: `char myLetter = 'D';`

4. `boolean`: This is a data type that can hold only two possible values: true or false. This data type is used for simple flags that track true/false conditions.

   Example: `boolean myBool = true;`

5. `String`: This is a data type that can hold a sequence of characters (text). String values must be surrounded by double quotes.

   Example: `String myText = "Hello";`

In your code, you have declared these variables and assigned them values. Then, you are printing out the values of these variables using `System.out.println()`.

# rules of naming a variable in Java

In Java, variable names are case-sensitive and must begin with a letter (A-Z or a-z), a currency character ($) or an underscore (_). After the first character, variable names can also contain digits (0-9).

Here are some rules and conventions for naming variables in Java:

1. Variable names cannot be the same as Java keywords or reserved words. For example, `int`, `class`, `public`, etc.

2. Variable names should not contain white spaces.

3. Although variable names can begin with a currency character or an underscore, it's not recommended as it makes the code harder to read.

4. Java follows camel case syntax for naming variables. It starts with a lowercase letter and the first letter of each subsequent concatenated word is capitalized. For example, `myVariableName`.

5. Variable names should be short yet meaningful. The choice of a variable name should be mnemonic i.e., designed to indicate to the casual observer the intent of its use.

6. One-character variable names should be avoided except for temporary "throwaway" variables. Common names for temporary variables are `i`, `j`, `k`, `m`, and `n` for integers; `c`, `d`, and `e` for characters.

7. If the name you choose consists of only one word, spell that word in all lowercase letters. If it consists of more than one word, capitalize the first letter of each subsequent word.

Here are some valid examples of variable names:

```java
String myString;
int counter;
float myFloatNum;
boolean isTrue;
char myLetter;
```

And here are some examples of invalid variable names:

```java
int 123abc; // Starts with a digit
String my String; // Contains a space
float float; // Same as a reserved word
```

# Keywords in Java
In Java, keywords are reserved words that are predefined and have special meanings to the compiler. They cannot be used as identifiers (variable names, method names, class names etc.) in your programs. Here are some of the keywords in Java:

1. `abstract`: Used to declare an abstract class or method, which can't be instantiated but can be subclassed.

2. `assert`: Used for debugging purposes to validate certain expressions.

3. `boolean`: A data type that can hold true or false.

4. `break`: Used to break out of a loop or a switch statement.

5. `byte`: A data type that can hold 8-bit data values.

6. `case`: Used in switch statements to mark blocks of text.

7. `catch`: Used in exception handling to catch exceptions.

8. `char`: A data type that can hold unsigned 16-bit Unicode characters.

9. `class`: Used to define a class.

10. `const`: Not used in Java.

11. `continue`: Used to skip the current iteration of a loop.

12. `default`: Used in a switch statement to mark the default block of code.

13. `do`: Used in control flow to declare a loop that will execute at least once.

14. `double`: A data type that can hold 64-bit floating-point numbers.

15. `else`: Used in control flow to declare an alternative block of code if the if condition is false.

16. `enum`: Used to define a fixed set of constants.

17. `extends`: Used in inheritance to specify that a class is a subclass of another class.

18. `final`: Used to indicate that a variable holds a constant value, a method cannot be overridden, or a class cannot be subclassed.

19. `finally`: Used in exception handling, contains block of code that will be executed whether or not an exception is thrown.

20. `float`: A data type that can hold 32-bit floating-point numbers.

21. `for`: Used to create a for loop.

22. `if`: Used in control flow to declare a block of code that will execute if a condition is true.

23. `implements`: Used in inheritance to specify that a class implements an interface.

24. `import`: Used to import a package into a Java source file.

25. `instanceof`: Used to check whether an object is an instance of a specific class or an interface.

26. `int`: A data type that can hold 32-bit signed integers.

27. `interface`: Used to declare an interface.

28. `long`: A data type that can hold 64-bit integers.

29. `native`: Used in methods to specify that the method is not implemented in the same Java source file, but rather in another language.

30. `new`: Used to create new objects.

31. `package`: Used to create a package, which is a grouping of related types.

32. `private`: An access modifier used to specify that a method or variable can be accessed only within its own class.

33. `protected`: An access modifier used to specify that a method or variable can be accessed within its own class, its subclasses, and classes in the same package.

34. `public`: An access modifier used to specify that a method or variable can be accessed from any class.

35. `return`: Used in methods to specify the value returned by the method.

36. `short`: A data type that can hold 16-bit integers.

37. `static`: Used to declare a method or variable that belongs to the class, rather than an instance of the class.

38. `strictfp`: Used to restrict the precision and rounding of floating point calculations to ensure portability.

39. `super`: Used in subclasses to refer to the superclass.

40. `switch`: Used in control flow to create a switch statement.

41. `synchronized`: Used to specify critical sections or methods in multithreaded code.

42. `this`: Used in methods or constructors to refer to the current object.

43. `throw`: Used to throw an exception.

44. `throws`: Used in method declarations to specify which exceptions are not handled within the method.

45. `transient`: Used in serialization to specify that a variable is not serialized.

46. `try`: Used in exception handling to specify a block of code in which exceptions may occur.

47. `void`: Used in methods to specify that the method does not return a value.

48. `volatile`: Used in multithreaded code to specify that a variable can be accessed by multiple threads and should not be cached.

49. `while`: Used to create a while loop.


# Operators in Java
In Java, operators are special symbols that perform specific operations on one, two, or three operands, and then return a result. The types of operators in Java include:

1. **Arithmetic Operators**: These are used to perform basic mathematical operations.
   - Addition (`+`)
   - Subtraction (`-`)
   - Multiplication (`*`)
   - Division (`/`)
   - Modulus (remainder) (`%`)
   - Increment (`++`)
   - Decrement (`--`)

2. **Relational Operators**: These are used to compare two values.
   - Equal to (`==`)
   - Not equal to (`!=`)
   - Greater than (`>`)
   - Less than (`<`)
   - Greater than or equal to (`>=`)
   - Less than or equal to (`<=`)

3. **Bitwise Operators**: These are used to perform operations on bits.
   - Bitwise AND (`&`)
   - Bitwise OR (`|`)
   - Bitwise XOR (`^`)
   - Bitwise Complement (`~`)
   - Left shift (`<<`)
   - Right shift (`>>`)
   - Zero fill right shift (`>>>`)

4. **Logical Operators**: These are used to perform logical operations (result in boolean value).
   - Logical AND (`&&`)
   - Logical OR (`||`)
   - Logical NOT (`!`)

5. **Assignment Operators**: These are used to assign values to variables.
   - Assign (`=`)
   - Add and assign (`+=`)
   - Subtract and assign (`-=`)
   - Multiply and assign (`*=`)
   - Divide and assign (`/=`)
   - Modulus and assign (`%=`)
   - Left shift and assign (`<<=`)
   - Right shift and assign (`>>=`)
   - Bitwise AND and assign (`&=`)
   - Bitwise XOR and assign (`^=`)
   - Bitwise OR and assign (`|=`)

6. **Ternary Operator**: This is a shorthand for the `if-then-else` statement.
   - `? :`

7. **Instanceof Operator**: This is used to check whether an object is an instance of a specified type (class or subclass or interface).
   - `instanceof`

8. **Type Comparison Operator**: This is used to compare the types of object and classes.
   - `instanceof`

# loops in java
In Java, there are three types of loops:

1. **For Loop**: A for loop is a control flow statement for specifying iteration, which allows code to be executed repeatedly. It is often used when the number of iterations is known.

   Example:
   ```java
   for(int i = 0; i < 5; i++) {
       System.out.println(i);
   }
   ```

2. **While Loop**: A while loop is a control flow statement that allows code to be executed repeatedly based on a given boolean condition. The while loop can be thought of as a repeating if statement.

   Example:
   ```java
   int i = 0;
   while(i < 5) {
       System.out.println(i);
       i++;
   }
   ```

3. **Do-While Loop**: The do-while loop is similar to the while loop except that the condition is not evaluated until the loop has been executed, so a do-while loop will execute at least once.

   Example:
   ```java
   int i = 0;
   do {
       System.out.println(i);
       i++;
   } while(i < 5);
   ```

Each of these loops is useful in different scenarios depending on the specific requirements of the situation.

# Access Modifiers in Java
In Java, there are four types of access modifiers:

1. **Private**: The access level of a private modifier is only within the class. It cannot be accessed from outside the class.

2. **Default (No Modifier)**: When no access modifier is specified for a class, method, or variable, Java will set the access level to default. The default access modifier is accessible only within the same package.

3. **Protected**: The access level of a protected modifier is within the class, the same package, and also in a subclass (even if it's in another package).

4. **Public**: The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the same package, outside the package, and in a subclass.

Here's an example of how these access modifiers are used in Java:

```java
public class MyClass {
    private int myPrivateVar; // Only accessible within MyClass
    int myDefaultVar; // Accessible within the same package
    protected int myProtectedVar; // Accessible within the same package and subclasses
    public int myPublicVar; // Accessible everywhere
}
```
These access modifiers are used to set the visibility and accessibility of classes, interfaces, variables, methods, and constructors in Java. They play a crucial role in encapsulation.

# Conditional Statement in Java
In Java, there are three types of conditional statements:

1. **If Statement**: It is used to specify a block of Java code to be executed if a condition is true.

   Example:
   ```java
   int x = 10;
   if(x > 0) {
       System.out.println("x is positive");
   }
   ```

2. **If-Else Statement**: It is used to specify a block of Java code to be executed if a condition is true. If the condition is not true, another block of code will be executed.

   Example:
   ```java
   int x = -10;
   if(x > 0) {
       System.out.println("x is positive");
   } else {
       System.out.println("x is not positive");
   }
   ```

3. **Switch Statement**: A switch statement allows a variable to be tested for equality against a list of values. Each value is called a case, and the variable being switched on is checked for each case.

   Example:
   ```java
   int day = 3;
   switch(day) {
       case 1:
           System.out.println("Monday");
           break;
       case 2:
           System.out.println("Tuesday");
           break;
       case 3:
           System.out.println("Wednesday");
           break;
       // cases for the rest of the week
       default:
           System.out.println("Invalid day");
           break;
   }
   ```

In addition to these, Java also has a ternary operator, which is a shorthand for the `if-then-else` statement.

Example:
```java
int x = 10;
String result = (x > 0) ? "x is positive" : "x is not positive";
System.out.println(result);
```
This operator checks the condition `x > 0`. If it's true, it assigns the string "x is positive" to the `result` variable. If it's false, it assigns the string "x is not positive" to the `result` variable.

