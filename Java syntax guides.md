- Main reference: [Java Syntax](https://www.w3schools.com/java/java_syntax.asp)
- Useful tool: [Java debugger - Java Tutor - Learn Java programming by visualizing code](https://pythontutor.com/java.html#mode=edit)

# Major principles 
- very line of code that runs in Java must be inside a `class`.
- printing 
	- `System.out.println`
	- `System.out.print` (no new line inserted)
- primitive variables [Java Variables](https://www.w3schools.com/java/java_variables.asp)
```java
int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";
```
- to instantiate a variable 
	- type should be specified 
	- non-primitive data types = reference types 
- strings can be concatenated using "+" as in python 
- if else 
	- short hand if-else (note ternary operator) [Java Short Hand If...Else (Ternary Operator)](https://www.w3schools.com/java/java_conditions_shorthand.asp)
	- use `switch` keyword to replace many if-elses
- for loop 
```java
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

//**Statement 1** is executed (one time) before the execution of the code block.
//**Statement 2** defines the condition for executing the code block.
//**Statement 3** is executed (every time) after the code block has been executed.
```
- use for-each loop to loop through elements in an array 
	- [Java For-Each Loop](https://www.w3schools.com/java/java_foreach_loop.asp)
	- in a for loop: `break` breaks the loop, `continue` breaks one iteration of a loop

# Methods 
- When defining a method 
	- the type of the parameters should be specified 
	- the return type of the method should be specified 
	- whether the method belongs to the class or if it belongs to an instance of the class 
		- if it belongs to the class, it is defined with `static` keyword 
- other interesting facts 
	- methods can be overloaded (multiple definitions share the same name) [Java Method Overloading](https://www.w3schools.com/java/java_methods_overloading.asp)
