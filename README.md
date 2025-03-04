# Project: MyMath

## Objectives

- Create a Java class with static methods.
- Implement basic mathematical operations.

## Program Description

A utility class in Java provides static methods that can be used across an application. The `Math` class in Java is an example of such a utility class, offering common mathematical functions.

In this project, you will create a utility class named `MyMath` that provides common mathematical methods similar to Java's `Math` class. These methods will help perform basic calculations without using loops or arrays.

## Program Specifications

Create a class named `MyMath`. The class must include the following static methods and constants:

### Constants:
- `public static final double PI = 3.141592653589793;`
- `public static final double E = 2.718281828459045;`

| Return Type | Method | Description |
|------------|--------|-------------|
| `double` | `add(double a, double b)` | Returns the sum of two integers. |
| `double` | `subtract(double a, double b)` | Returns the result of subtracting the second integer from the first. |
| `double` | `multiply(double a, double b)` | Returns the product of two integers. |
| `double` | `divide(double a, double b)` | Returns the result of dividing the first integer by the second. The divisor `b` cannot be zero. |
| `double` | `max(double a, double b)` | Returns the greater of two integers. |
| `double` | `min(double a, double b)` | Returns the smaller of two integers. |
| `boolean` | `isEven(int a)` | Returns `true` if the integer is even, `false` otherwise. |
| `boolean` | `isOdd(int a)` | Returns `true` if the integer is odd, `false` otherwise. |

### Notes:
- You **cannot** use the `Math` class in your implementation.
- In the `divide` method, if the divisor is zero, the program should terminate immediately with an appropriate error message. Use `System.exti(1)` to terminate the program.

## Sample Test
The following tester class should be saved in a separate file named `TestMyMath.java`.

```java
public class TestMyMath {
    public static void main(String[] args) {
        System.out.println(MyMath.add(3, 5));    // 8.0
        System.out.println(MyMath.subtract(10, 4)); // 6.0
        System.out.println(MyMath.multiply(3, 4));  // 12.0
        System.out.println(MyMath.divide(8, 2));    // 4.0
        System.out.println(MyMath.max(7, 9));      // 9.0
        System.out.println(MyMath.min(7, 9));      // 7.0
        System.out.println(MyMath.isEven(10));     // true
        System.out.println(MyMath.isOdd(11));      // true
        System.out.println(MyMath.PI);      // 3.141592653589793
        System.out.println(MyMath.E);      // 2.718281828459045
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

