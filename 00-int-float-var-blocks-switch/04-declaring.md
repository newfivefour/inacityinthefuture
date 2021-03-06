# 4. Telling Java about your data

We currently print data without changing it:

**code sample 0.4.0**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("My age is: " + 36 + ".");
  }
}
```

But computer programs need to change data. For example, your score in a computer game.

When we need to change data, we first tell Java about our data.

So we will learn our second statement: telling Java about our data.

## Introducing variables

We need to tell Java about data that will change. 

We can also say: we need to tell Java about data that will *vary*.

When we need to *vary* data, we use **variables**.

So a **variable** is some data that will vary.

## What is a variable made of?

A variable is made of two things:

0. A variable data type
0. A variable name

We looked at data types previously: string, int and float.

A variable name can be anything you want.

## Declaring a variable

We **declare** a variable when we tell Java about the variable's *data type* and *name*.

A computer program will contain many **declarations**.

## What does a variable type look like?

We know four types of data: a string, an int, a float and a boolean.

* An int variable looks like this: `int something`
* A float variable looks like this: `float something`
* A string variable looks like this: `String something`

*Note* that a string has a **uppercase** S. In later lessons, we will explain why.

## What can I name my variable?

We said it can be whatever you want. But:

* It must start with a letter: `String hello`.
* Or can start with or include **underscores**: `String _hello`.
* And it *must not* include spaces: `String helloIAmALongerName`.
* And it can include numbers, but *not* at the beginning: `String hello43`.

## Examples

This is a string variable named `hello`:

```java
String hello;
```

This is a int variable named `age`:

```java
int age;
```

This is a float variable named `score`:

```java
float score;
```

When we declare a variable, we make a **statement**. And you end statements with a semi-colon, `;`.

## We can declare a variable ONLY ONCE

If you try to **declare** two variables with **same** name, Java will get confused. Java will complain. A lot!

**code sample 0.4.1**
```java
class Main {
  public static void main(String[] args) {
    // THE BELOW WILL NOT WORK!!!!!!
    String name;
    String name;
  }
}
```

## Exercise

The exercises will be in the next chapter.

But you need to answer the questions below.

## Questions to answer

0. What is a variable?
0. What two things make up a variable?
0. What is declaring a variable?
0. Give an example of an int variable.
0. Give an example of an string variable.
0. Give an example of a float variable.
0. What data type starts with a uppercase letter?
0. What happens when we declare two variables with the same name?
