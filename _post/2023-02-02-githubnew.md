---
title: "New Programming Language"

What is Java?

Java is a high-level programming language developed by Sun Microsystems (now owned by Oracle) in the mid-1990s. It is a class-based, object-oriented language that is designed to be portable and run on any platform, allowing developers to write code once and run it anywhere. Java is widely used for developing desktop applications, mobile apps, and web-based applications, as well as for building server-side applications and games.

why java?

Platform Independent: Java code can run on any device with a Java Virtual Machine, which eliminates the need for recompilation.

Object-Oriented: Java supports object-oriented programming, which allows for the creation of modular and reusable code.

Robust: Java has strong memory management and automatic exception handling, making it more reliable and less prone to crashes.

Secure: Java is designed to be secure, with built-in security features such as type-safe objects and automatic memory management.

Large Community: Java has a large, active developer community that provides ongoing support, development, and improvement to the language.

Versatile: Java can be used for a variety of applications, including web, mobile, desktop, and enterprise applications.

Scalable: Java can handle high-volume, high-performance applications by using multiple threads to handle multiple tasks simultaneously.

Variables in java:

In Java, a variable is a named storage location that holds a value of a specific data type. There are several types of variables in Java, including:

Primitive Variables: These are the basic data types in Java, such as int, float, double, char, and boolean.

Reference Variables: These are variables that refer to objects, and include arrays and class objects.

Local Variables: These are variables declared within a method or block, and are only accessible within that scope.

Instance Variables: These are variables that belong to an object, and are accessible from any method within the object's class.

Static Variables: These are variables that belong to the class, rather than to an individual object, and are shared among all objects of the same class.

All variables in Java must be declared before they can be used, and the declaration must specify the data type of the variable. The value of a variable can be changed throughout the life of a program.
public class Main {
   public static void main(String[] args) {
       // Declare an int variable
       int age;
       // Assign a value to the int variable
       age = 30;
       // Print the value of the int variable
       System.out.println("My age is: " + age);
 
       // Declare a double variable
       double salary;
       // Assign a value to the double variable
       salary = 75000.0;
       // Print the value of the double variable
       System.out.println("My salary is: " + salary);
 
       // Declare a boolean variable
       boolean isEmployed;
       // Assign a value to the boolean variable
       isEmployed = true;
       // Print the value of the boolean variable
       System.out.println("Am I employed? " + isEmployed);
   }
}
In this example, we declare three variables of different data types (int, double, and boolean) and assign values to them. The values of the variables can be printed to the console using the System.out.println() method.

1) java if, if..else statements

The syntax of the if statement in java is:

The if statement in Java is used to conditionally execute a block of code based on whether a given condition is true or false. The basic syntax of an if statement is as follows:

scss
Copy code
if (condition) {
    // code to be executed if the condition is true
}
The else statement is used in conjunction with the if statement to provide an alternative block of code to be executed if the condition in the if statement is false. The basic syntax of an if...else statement is as follows:

vbnet
Copy code
if (condition) {
    // code to be executed if the condition is true
} else {
    // code to be executed if the condition is false
}
Here is an example that demonstrates how to use if...else statements in Java:

csharp
Copy code
public class Main {
   public static void main(String[] args) {
       int age = 25;
 
       if (age >= 18) {
           System.out.println("You are an adult.");
       } else {
           System.out.println("You are a minor.");
       }
   }
}
In this example, the if statement checks if the value of the age variable is greater than or equal to 18. If the condition is true, the message "You are an adult." is printed. If the condition is false, the message "You are a minor." is printed.






How did I learn?

https://en.wikipedia.org/wiki/Java_(programming_language)

https://www.tutorialspoint.com/java/index.htm
---
