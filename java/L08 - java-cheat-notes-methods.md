# Methods

Methods are extensions of a class, they allows the class to perform multiple operations.

Those operations are made inside the method block only.

Methods can return something to the caller or not, it is defined on his signature or just be void, witch has no return.

Methods also can require parameters to perform his operations, theses parameters are also defined on his signature.

## Rules for namin methods

It's not required, but standards make your life easier.

Use meaninfull names and CamelCase

names must be a verbs, like

```java
public Customer createCustumer();
```

methods must have a single responsability, don't create methods like:

```java
public void calculatePrint();
```

In java world, there's no global methods.