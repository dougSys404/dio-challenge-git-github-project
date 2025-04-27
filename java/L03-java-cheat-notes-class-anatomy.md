# Java Sintax


Use english words to write methods, attributes.

Class structre.

```java
public class MyClass{
    // your code here
}
```

#### Where:
- **public** -> Access modifier
- **MyClass** -> Your class name (For convention, start always Uppercase and use camel case)
- **{}** -> block class code

## Class example

```java
public class MyClass{
    public static void main(String args[]){
        System.out.println("Hello world");
    }
}
```

#### Where:

- **public static void main(String args[])** -> Entrypoint application / Where your program runs
- **System.out.println()** -> print on console

## Naming standard

Name standard defines how we write java code in easy way and readble arround community, it makes your job easier and mantainable.

File name:

Always the first letter has to be uppercase, for complex names, make the first letter uppercase.

Ex:

Class for external suppliers

File name and classe name: **ExternalSuppliers**

**CamelCase**

CamelCase is a way to separate the words in a phrase by making the first letter of each word capitalized and not using spaces.

**Meaning**

Always give to classes, methods and attributes meaningfull names, in other words, you see it, you'll understand.

**Variables:**

Just one difference, the first letter of the fist name (in case of complex names) has to be lowercase

Ex:

Name of the supplier: **supplierName**

In case of variables non multable, use give full name uppercase, ex:

```java
private String BR = "Brasil"
```

In this case, we can also give the modifier "final" for the attribute, it makes non-multable value, ex:

```java
private final String BR = "Brasil"
```

**Important**

- Don't use spaces, special language words and special characters
- Underscore and ampersand are allowed to begin variables name
- Don't start with numbers


## Declaring variables

[type] [name] = [give value(Optional)]

**Example**

```java
int accountNumber;
boolean accountValid = true;
String custumerName = "Jonh Green";
char accountType = 'B';
```

## Methods

Methods is an actions of a class, it gives operations for an object, like, safety access to attirbutes, validations and etc.

[Return type] [Method name] (Parameters) {block code}

**Example**

```java
public void createCustomer(String name, char accountType, double inicialDeposit) {
    // your code here
}
```

### Usage so far

```java
public class BankAccount{
    String customerName;
    double amount = 0.0;
    char accountType;
    boolean accountValid = true;

    public void createCustomer(String customerName, char accountType, double inicialDeposit) {
        this.customerName = customerName;
        this.inicialDeposit = amount;
        this.accountType = 'B';
    }
}
```

## Indentation

Refers to consistent spacing or tab used at the begining line of a code to visually organize it.


## Files and folders structure

Java organizes project structures into packages, there's a convention for that, let's take a look:

Folder structure on OS:

/projects/java-app/

packages structure:

com.java-app

Inside these packages (folders) we organize our files into subpackages.

There's some patterns for that, like

**com.java-app.util** -> libs
**com.java-app.models** -> class models
**com.java-app.controllers** -> API Endpoints
**com.java-app.services** -> API Services

### Usage so far

```java
package com.java-app.models;

public class BankAccount{
    String customerName;
    double amount = 0.0;
    char accountType;
    boolean accountValid = true;

    public void createCustomer(String customerName, char accountType, double inicialDeposit) {
        this.customerName = customerName;
        this.inicialDeposit = amount;
        this.accountType = 'B';
    }
}
```