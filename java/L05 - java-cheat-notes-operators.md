# Operators

Operators are special symbols used in Java to represent operations to be performed during the execution of the code. The types of operators are:

- Arithmetic
- Unary
- Relational
- Logical
- Ternary

## Arithmetic Operators

They perform mathematical operations.

Assignment (`=`) → Defines the initial value or overwrites the value of a variable. Another use of the assignment operator is to initialize an object.

Example:
```java
String name = "John Green";
int age = 22;
double weight = 68.5;
char gender = 'M';
boolean organDonor = true;
Date birthDate = new Date();
```

Other arithmetic operators are:
Division (`/`), addition (`+`), subtraction (`-`), and multiplication (`*`).

Examples:

```java
double addition = 10.5 + 15.7;
int subtraction = 113 - 25;
int multiplication = 15 * 7;
int division = 15 / 3;
int division2 = 18 % 3;
double result = (10 * 7) + (20 / 4);
```

**IMPORTANT** → THE ADDITION OPERATOR (`+`) IS ALSO USED FOR TEXT CONCATENATION

Example:

```java
String fullName = "John" + " " + "Green";
```

## Unary Operators

Unary operators, when applied together with an operand, perform basic tasks such as incrementing, decrementing, or inverting numeric and boolean values.

- Positive operator (`+`) → Considers or forces values to be positive
- Negative operator (`-`) → Negates a value or arithmetic expression
- Increment operator (`++`) → Increases the value by 1
- Decrement operator (`--`) → Decreases the value by 1
- Logical negation operator (`!`) → Negates the value of a boolean expression

## Ternary Operator

The ternary conditional operator is a shorthand way to define a condition and select between two values.

It is an evolution of the traditional "if" structure, making the code simpler and written in a single line.

The ternary operator is represented by the symbols `?` and `:`.

```java
[condition] ? [value if true] : [value if false];
```

**Example:**

```java
int number1, number2;
number1 = 5;
number2 = 6;
String result;
if (number1 == number2){
    result = "true";
} else {
    result = "false";
}

// Using the ternary operator

result = number1 == number2 ? "true" : "false";
```
