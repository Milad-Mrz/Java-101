## Java-101
This is a series of Java Tutorials for beginners like me, Java is a popular programming language with a number of advantages:

- Object-oriented: Java is an object-oriented programming language, which means that it is based on the concept of objects and classes. This makes it easier to write, understand, and maintain code, as well as to reuse code in multiple projects.

- Platform-independent: Java programs are compiled into bytecode, which can be run on any device that has a Java Virtual Machine (JVM) installed. This makes it easy to develop programs that can run on any operating system or device.

- Secure: Java has a number of built-in security features, such as the Java Security Manager and the Java Cryptography Extension (JCE), which make it a secure language for developing applications.

- Robust: Java has strong type checking and exception handling features, which help to prevent errors and make programs more robust.

- High-performance: Java programs are compiled into native code and optimized for performance, making it a good choice for developing high-performance applications.

- Widely used: Java is used in a wide range of applications, from web servers and mobile apps to scientific simulations and financial software. As a result, it is a widely-used and in-demand language, with a large community of developers and a wealth of resources and libraries available.

Java is a complex programming language with a large number of features and concepts that can take months or even years to fully understand and master. However, if you have some programming experience and just want to get a basic understanding of Java syntax and concepts, it is possible to get a rough idea of the language in a short period of time.

Here are the first steps to start with Java!
- Install a Java development environment: You will need to install a Java Development Kit (JDK) and a text editor or Integrated Development Environment (IDE) to write and run your Java code. Some popular IDEs for Java include Eclipse, IntelliJ, and NetBeans.

- Learn the **basic syntax**: Java is a C-style language, which means that it has a similar syntax to other languages like C, C++, and C#. Start by learning the basic syntax of Java, including the structure of a Java program, variables, data types, operators, and control structures like loops and conditionals.

- Understand **object-oriented programming**: Java is an object-oriented programming language, which means that it is based on the concept of objects and classes. Familiarize yourself with the key concepts of object-oriented programming, such as inheritance, polymorphism, and encapsulation.

- Practice writing code: The best way to learn any programming language is by writing code. Try working through some basic Java exercises or challenges to get a feel for the language and how to use it to solve problems.

Remember that learning any programming language requires a lot of practice and dedication. While it is possible to get a basic understanding of Java in one day, becoming proficient in the language will take significantly longer.


**1- Java basic syntax**

Every Java file ends in *.java, and it should contain a class inside with the **same name** which starting with capital letter, and then you should place a main method/function or void inside that class. name of the void must be in small letters.
The braces { } indicate the scope of the structure involved, like a class or the main method. A method is a function belong a class


```
public Class Main{
    public void main(){
        ...
    }
}
```

**public:** is access modifier.  <br />
**Class:** is group of functions.  <br />
**void:** is the phrase used for writing functions.  <br />

**! Remember:** After every line of command except **if**, you must place a **semicolon ;** at the end of the line.


**Data types:**

    int hoursInADay = 24, dayInAYear = 365;
- **int** to store integers, that is, numbers without decimal digits.
- **double** to store numbers with decimal digits.
- **boolean** to store true/false values.
- **String** to save literal messages.

**! Hint:** you can adjust data types during calculations.      

```
speed = kilometers / (double) hours; 
```

**Boolean operators:**
- NOT: !
- AND: &&
- OR: ||

**! Hint:** boolean data can be valued by operations such below.
```
int number1 = 1, number2 = 2; 
boolean value1 = number1 < number2;
```
or
```
(!true==false) != (b+c/a > a-b*c)
```

**Comparison operators:**
- Equal to:	==
- Different than / not equal to: !=
- Less than: <
- Less than or equal to: <=
- Greater than:	>
- Greater than or equal to: >=

**The if declaration**
```
if (a >= b) 
{
    ...;
}
else
{
    ...;
}
```



**Print:**
- System.out.print()	Prints a message in the console.
- System.out.println()	Prints a message in the console, then ends the line. <br />


**Shortcut operators**
```
a = a + 1; -> a++;
b = b - 1; -> b--;
c = c + 2; -> c += 2;
d = d - 3; -> d -= 3;
e = e * 4; -> e *= 4;
f = f / 5; -> f /= 5;
g = g % 6; -> g %= 6;
```