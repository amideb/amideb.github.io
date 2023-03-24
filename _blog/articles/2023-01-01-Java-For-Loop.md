---
layout:  post
title:  For Loop
date:   2023-01-01 12:31:19
summary: Java Tutorial For Loop
categories: SwJavaProgrammers
permalink:  /java-for-loop
image: /images/spring-boot-category.png
---


### Java Tutorial: For Loop

In Java, the `for` loop is used to repeatedly execute a block of code until a certain condition is met. It is a commonly used looping construct that is used in many programming scenarios. In this tutorial, we will explore the syntax and usage of the `for` loop in Java, and provide some examples to help you get started.

#### Syntax

The syntax for the `for` loop in Java is as follows:

```
`for (initialization; condition; increment/decrement) {
    // code to be executed
}
```

The `for` loop consists of four parts:

1.  **Initialization**: This is where you initialize the loop counter variable. It is executed only once, at the beginning of the loop.
2.  **Condition**: This is where you define the condition that must be true for the loop to continue. If the condition is false, the loop terminates.
3.  **Increment/Decrement**: This is where you update the loop counter variable. It is executed at the end of each iteration of the loop.
4.  **Code Block**: This is the block of code that is executed repeatedly as long as the condition is true.

#### Example

Here's an example of how to use the `for` loop to print the numbers from 1 to 10:

```
for (int i = 1; i <= 10; i++) {
    System.out.println(i);
}
```

In this example, we initialize the loop counter variable `i` to 1, and specify the condition that the loop should continue as long as `i` is less than or equal to 10. After each iteration of the loop, we increment `i` by 1 using the increment operator `++`. Finally, we print the value of `i` using the `System.out.println()` method.

#### Coding Exercises

##### Exercise 1

Write a Java program that uses a `for` loop to print the even numbers from 2 to 10.

```
for (int i = 2; i <= 10; i += 2) {
    System.out.println(i);
}
```

In this example, we initialize the loop counter variable `i` to 2, and specify the condition that the loop should continue as long as `i` is less than or equal to 10. After each iteration of the loop, we increment `i` by 2 using the increment operator `+= 2`. Finally, we print the value of `i` using the `System.out.println()` method.

##### Exercise 2

Write a Java program that uses a `for` loop to calculate the sum of the first 10 natural numbers.

```
int sum = 0;
for (int i = 1; i <= 10; i++) {
    sum += i;
}
System.out.println("Sum of first 10 natural numbers is: " + sum);
```

In this example, we initialize the loop counter variable `i` to 1, and specify the condition that the loop should continue as long as `i` is less than or equal to 10. After each iteration of the loop, we add the value of `i` to the `sum` variable. Finally, we print the value of `sum` using the `System.out.println()` method.

#### Conclusion

The `for` loop is a powerful and flexible looping construct that can be used to iterate over a range of values in Java. By mastering the syntax and usage of the `for` loop, you can simplify your code and make it more efficient. We hope that this tutorial has provided you with a good foundation for using the `for` loop in your Java programs.