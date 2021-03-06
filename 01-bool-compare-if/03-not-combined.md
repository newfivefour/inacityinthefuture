# 3. Boolean "not" and combined logic

## Boolean not

The final boolean operation is the **boolean not**. And this is very simple. 

If the boolean is `true`, a **boolean not** makes it `false`. If the boolean is `false`, a **boolean not** makes it `true`.

We type `!` before a boolean variable to use a **boolean not**

**code sample 1.3.0**
```
class Main {
  public static void main(String[] args) {
    boolean hotWeather = true;
    System.out.println("The weather is hot: " + hotWeather);
    hotWeather = !hotWeather;
    System.out.println("The weather is hot: " + hotWeather);
  }
}
```

This output from this program is:

```
The weather is hot: true
The weather is hot: false
```

## Combined boolean logic

We can combine boolean logic.

For example, we can say: "If it is hot and is not night-time, I will go outside. However, if I have no food I will go outside, in any weather or anytime."

Let's imagine: `It's hot but it's night-time. So we stay home. But we need food, so we go outside.`

In Java this is: 

**code sample 1.3.1**
```
class Main {
  public static void main(String[] args) {
    boolean nighttime = true;
    boolean hot = true;
    boolean needFood = true;
    boolean iWillGoOutside = !nightime && hot || needFood;
    System.out.println("I will go outside: " + iWillGoOutside);
  }
}
```

0. `nighttime` is `true` and `hot` is `true`.
0. We use `!nighttime` so this makes it `false`.
0. So `!nighttime && hot` is `false && true`
0. And that means (so far) `iWillGoOutside` is `false`.

This is the same as the above sentence: "It's hot but it's night-time. So we stay home"

Let's take this and look at the next part: "But we need food, so we go outside."

0. We take that `false` from above and do `false || needFood`.
0. `needFood` is `true` so this makes `false || true`
0. So `iWillGoOutside` is `true`.

## Excersise

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_3_1 (click on the pen icon near the top left)
0. Create a program with two booleans `tastyBreakfast` which is `false`, and `fullStomach` which is `false`.
0. Print out the string `"I will eat breakfast: "` 
0. Then the value of the following boolean logic: "if the breakfast is tasty or I do not have a full stomach", 

And 

0. Start a new Java program on https://repl.it
0. Save this file as java_exercise_1_3_1 (click on the pen icon near the top left)
0. Create a program with three booleans `morning`, `hungry` and `haveOtherFood` which are all `false`.
0. Print out the string `"I should eat breakfast at home: "` 
0. Then the value of the following boolean logic: "If it is morning and I am hungry, or if I do not have any other food." 

## Questions to answer ##

0. What is a "boolean not"?
0. Give an example of a "boolean not".
