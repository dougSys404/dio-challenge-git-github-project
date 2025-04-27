# Types and variables

Data types are reserved word used to describe base data types in java, types itself witch needs to be manipulated for programs constuctions. These types are known as *Primitive Types*

The primitive types in java:

- **int**  --> -2.147.483.648 / 
- **byte** --> -128 / 127
- **short** --> -32.768 / 
- **long** --> -9.223.372.036.854.775.808 / 9.223.372.036.854.775.807
- **float** --> -3,4028E + 38 / 3,4028E + 38
- **double** --> -1,7976E + 308 / 1,7976E + 308
- **boolean** --> true / false
- **char**

They aren't object, they represent gross values, they are stores inside memory stack



# Variables

Variable is an indentification of a space created in memory by the program. They are used to represent values witch can be used in our operations.

#### How to declare a variable

[type] [name] = [optional attr.]

**Example**

```java
int age;
double salary = 2.500; // 2,5 value
double salary2 = 2500; // 2500 value
String name = "John Green";
```

Variables as the name itself says, the value can change on the execution, but if ou need a non-changeble varable, we declare it as a constant

```java
final int NON_CHANGEBLE_VARIABLE = 500;
```

For convention, constants are name different from common variables, the whole name are uppercase and for complex names, use _ as a separator