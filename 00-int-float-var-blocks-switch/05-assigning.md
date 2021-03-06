# 5. Giving your variable a value

We previously declared a variable.

Now we will give that variable a value (i.e. "Aaron", 36, 3.14f, etc)

This will be the third statement that we can use.

## How can we put data in our variable?

When we give a variable a value, we **assign** a value to variable. 

When we assign a value to a variable, the variable and value *must* have the same data type (`int` and `36`, `String` and `"Aaron"`, etc). If it does not, Java will complain. A lot!

When we assign we

0. Type the variable name
0. Type a space
9. Type the equals sign, `=`
0. Type a space
0. Type the value
0. Type a semi-colon, `;` (because this is a statement)

For example, we assign `"Aaron"` to the `name` variable by writing:

```java
name = "Aaron";
```

For example, we assign `36` to the `age` variable by writing:

```java
age = 36;
````

For example, we assign `10.50` to the `score` variable by writing:

```java
score = 10.50f;
````

## Printing the variable

We declared a variable last lesson. And we assigned a value to a variable in this lesson. 

We can now use the variable name to print it.

**code sample 0.5.0**
```java
class Main {
  public static void main(String[] args) {
    int age;
    age = 36;
    System.out.println("My age is: " + age);
  }
}
```

This will output:

```
My age is: 36
```

## We can assign a value to a variable many times

We can change (or vary) our data by assigning a new value to it.

For example:

**code sample 0.5.1**
```java
class Main {
  public static void main(String[] args) {
    int age;
    age = 36;
    System.out.println("One year passes.");
    age = 37;
    System.out.println("One year passes.");
    age = 38;
    System.out.println("My age is now: " + age);
  }
}
```

The output is:

```
One year passes.
One year passes.
My age is now: 38
```

*Note:* We can assign a value to a variable multiple times. But we can only declare a variable (with the same name) once.

## We can declare and assign a variable on the same line

We often declare and assign a variable on the same line.

For example: `String name = "Aaron";`.

The above program is exactly the same as above:

**code sample 0.5.2**
```java
class Main {
  public static void main(String[] args) {
    int age = 36;
    System.out.println("One year passes.");
    age = 37;
    System.out.println("One year passes.");
    age = 38;
    System.out.println("My age is now: " + age);
  }
}
```

## Exercise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_0_5_0 (click on the pen icon near the top left)
0. Write a program that: declares a float value with variable name `balance`, assign the value `100.0` to it, print it, assign the value `90.0` to the same variable, then print it again.

## Questions to answer

0. Give an example of an int value.
0. Give an example of a float value.
0. Give an example of a string value.
0. What is assigning a variable?
0. Give an example of assigning an int value to a variable.
0. Give an example of assigning a float value to a variable.
0. Give an example of assigning a string value to a variable.
0. What happens when the data types of the value and variable are different?
