# Project: MyMath

## Objectives

- Create a Java class with static methods.
- Implement basic mathematical operations without using loops or arrays.

## Program Description

A utility class in Java provides static methods that can be used across an application. The `Math` class in Java is an example of such a utility class, offering common mathematical functions.

In this project, you will create a utility class named `MyMath` that provides common mathematical methods similar to Java's `Math` class. These methods will help perform basic calculations without using loops or arrays.

## Program Specifications

Design a class named `MyMath`. The class must include the following static methods:

| Return Type | Method | Description |
|------------|--------|-------------|
| `int` | `add(int a, int b)` | Returns the sum of two integers. |
| `int` | `subtract(int a, int b)` | Returns the result of subtracting the second integer from the first. |
| `int` | `multiply(int a, int b)` | Returns the product of two integers (without using `*`). |
| `double` | `divide(int a, int b)` | Returns the result of dividing the first integer by the second (without using `/`). Assume `b` is not zero. |
| `int` | `max(int a, int b)` | Returns the greater of two integers. |
| `int` | `min(int a, int b)` | Returns the smaller of two integers. |
| `boolean` | `isEven(int a)` | Returns `true` if the integer is even, `false` otherwise. |
| `boolean` | `isOdd(int a)` | Returns `true` if the integer is odd, `false` otherwise. |

### Notes:
- You **cannot** use the `Math` class in your implementation.
- The `multiply` method should use repeated addition instead of the `*` operator.
- The `divide` method should use repeated subtraction instead of the `/` operator.

## Sample Test

```java
public class TestMyMath {
    public static void main(String[] args) {
        System.out.println(MyMath.add(3, 5));    // 8
        System.out.println(MyMath.subtract(10, 4)); // 6
        System.out.println(MyMath.multiply(3, 4));  // 12
        System.out.println(MyMath.divide(8, 2));    // 4.0
        System.out.println(MyMath.max(7, 9));      // 9
        System.out.println(MyMath.min(7, 9));      // 7
        System.out.println(MyMath.isEven(10));     // true
        System.out.println(MyMath.isOdd(11));      // true
    }
}
```

## Coding Standards

1. Follow the program specifications.
2. Use meaningful variable names.
3. Remove any auto-generated comments.
4. Use JavaDoc to document your code.
5. Include a program description and attribute yourself using the `@author` tag.
6. Your output should be user-friendly.

For documentation reference: [JavaDoc](https://en.wikipedia.org/wiki/Javadoc)

