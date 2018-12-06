
# 1. Getting started - Printing our name

## Instructions (or statements)

We said a Java program contains instructions for the computer.

We call these instructions **statements**. Around 75% of all code is statements. 

In Java every statement ends with a semi-colon, `;`. Remember this fact!

## Basic form of Java

Before we learn our first statement, we will look at the basic form of Java:

```java
class Main {
  public static void main(String[] args) {
    ...
  }
}
```

There is a lot here we don't understand. We will learn about it all in later lessons.

For this lesson we will start coding on line three.

We will ignore the rest for the moment.

## Our first statment: printing

We will learn how to print to the screen.

0. The first thing we type is `System.out.println`. 
0. Then we type an opening parenthesis, `(`. 
0. Then we type what you want to print (see the next section).
0. Then we type a closing parenthesis, `)`.
0. And all statements end with a semi-colon, so we type `;`.

## Printing a **string**

We are going to print some text. In Java text is called a **string**.

A **string** must be surrounded by double quotation marks: `"Hello"`.

*Only* strings are surrounded by quotation marks.

So our final statement looks like this:

```java
System.out.println("Hello, world!");
```

When we add this statement to the basic form of Java, it looks like this:

**code sample 1.0**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("Hello, world!");
  }
}
```

A program can, and normally does, have many statements.

**code sample 1.1**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("Hello, world!");
    System.out.println("How are you?!");
  }
}
```

## Comments

**Comments** are lines Java ignores.

Comments start with two forward slashes: `//`. 

We use them to keep notes about a program. Or to help a friend understand our program.

Another way to write them is: `/* This is a comments */`

Here is a the above program with a comment. Normally your comments will be more useful.

**code sample 1.2**

```java
class Main {
  public static void main(String[] args) {
    System.out.println("Hello, world!");
    // Let's be polite and ask the world a question
    System.out.println("How are you?!");
  }
}
```

## Start coding ##

0. Make a github account on https://github.com
0. Go to https://repl.it and press signup, then press login, and login with your Github account
0. Press the add button
0. Select the Java language
0. Type in the code you saw in code sample 1.1.

## Exercises ##

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_0 (click on the pen icon near the top left)
0. Write a program that has two statements: the first prints "My name is <insert your name here>!"`, and the second prints "Goodbye!".
0. Add a comment that says what your program does!

## Questions to answer ##

0. What is a comment?
0. What does a comment look like?
0. What is a string?
0. What is a string surrounded by?
0. What is a statement?
0. What must a statement end with?
0. What do you type to print something to the screen?