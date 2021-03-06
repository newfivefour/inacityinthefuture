# 3. Concatenation - Printing nicer things

## How we currently print

In the last lesson, we printed either a string, an int or a float.

For example:

**code sample 0.3.0**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("My age is: ");
    System.out.println(36);
  }
}
```

This will print

```
My age is:
36
```

But we can make printing data types nicer. We can join them together.

## Printing joined data types

We can print a string together with another type with the `+` symbol.

**code sample 0.3.1**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("My age is: " + 36 + ".");
  }
}
```

The output will be:

```
My age is: 36.
```

We can do this for floats too.

**code sample 0.3.2**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("This is an int: " + 42 + ".");
    System.out.println("This is an float: " + 3.1415f + ".");
  }
}
```

The output will be:

```
This is an int: 42.
This is an float: 3.1415.
```

When we join a string with another type, this is called **concatenation**: we **concatenate** a string and another value.

When we concatendate two values, the first value *must* be a string.

## Concatenating two strings

We can also concatenate two strings:

**code sample 0.3.3**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("My name is " + "Aaron.");
  }
}
```

This will print the same as:

**code sample 0.3.4**
```java
class Main {
  public static void main(String[] args) {
    System.out.println("My name is Aaron.");
  }
}
```

## Exercise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_0_3_0 (click on the pen icon near the top left)
0. Write a program that concatenates your name, a space, a number, a space, a float.

## Questions to answer

0. What is concatenation?
0. What data types can we concatenate?
0. When we concatenate type of data, what data type must we start with?
