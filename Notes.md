# Basic Notes
## Making comments in Java Code can be done as followed: 
// Single-Line syntax 

/* 
Multiline Notes can be done this way
*/

Javadoc comment can be done as followed: 
Javadocs are used to create documentation for APIS. 
When writing Javadoc comments keep in mind that they might be read by your users.
/**
* The follow class accomplishes the following
*/

## Semicolons matter

Remember to end commands with a ; as whitespace is ignored in Java. A ; ends a command and allows a new one to get started.

## Compilation 

Java is a compiled programming language. A .java file is transformed into byte code by a compiler before it is executed by a Java Virtual Machine (JVM)

### Compiling a java file we can use the command: 
javac 

Once a .java file is compiled it will give you a class component that we can execute with 
java ClassName

## JShell
If you are wanting to run simple Java commands you can use jshell. This does not replace the need for an IDE
In the command prompt you can type jshell then type in /help to give you a list of commands that you can use.


## Data Types

Whole Numbers which are int primitive data type
To declare a variable type of int, the int keyword comes before the variable name: 
int yearJavaCreated = 1995;

The next number type is double primitive data type. double can hold decimals.
double price = 9.99;

True or False: booleans
They have the keyword boolean in the very front. 
boolean javaIsCoffee = false;

char data type can hold any character, letter, space, or punctuation mark.

String 
Strings are objects
Strings hold sequences of characters. 
In strings the backslash \ has a different meaning. Escape characters begin with the character \. 
\" Allows us to add quotation marks to a string value. 
Double \\ Places a backslash in our string.
String stringName = "New String" or 
String stringName = new String("New String");

Java programs will not compile if a variable is assigned a value of an incorrect type. This is because Java Programming language has static typing. This is a BUG (declaration bug).

## Naming Variables 

Naming Variables according ot convention leads to clear, readable, and maintainable code. 

Use descriptive names that don't have ambiguity

## Arithmetic 
The operations all work the same as other coding languages. 




