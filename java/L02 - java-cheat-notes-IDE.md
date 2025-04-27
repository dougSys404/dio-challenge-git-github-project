# IDEs for Java Coding

An Integrated Development Environment (IDE) is **not** required to write Java code; a simple text file is enough.

However, an IDE provides a lot of resources to the developer to write programs correctly and make the job easier.

## Resources available in IDEs

- Auto-complete/IntelliSense features
- Code formatting for syntax, variables, methods, classes, objects, etc.
- Syntax error detection
- Compilers and processors
- Debugging tools

There are many IDEs available — some free, some paid. Some of them offer specific features for the Java language, while others are more generic but still great for coding.

## Some examples of IDEs

- JetBrains IntelliJ
- Apache NetBeans
- Microsoft Visual Studio Code
- Eclipse

> Try all of the IDEs before choosing one as your main coding environment.

Nowadays, IDEs usually offer full integration with GitHub or other Git platforms.

---

# Before Choosing Your IDE

1. Install JDK / Java SDK
2. Download the installer according to your operating system (OS)
3. Install it
4. After installation, check the environment variables:

## Windows CLI

```bash
echo %JAVA_HOME%
java -version
```

## Linux CLI

```bash
echo $JAVA_HOME
java -version
```

## macOS CLI

```bash
echo $JAVA_HOME
java -version
```

---

# In Case You Need to Set the Variables

## Windows CLI

```bash
set JAVA_HOME=C:\path\to\your\jdk
set PATH=%JAVA_HOME%\bin;%PATH%
```

## Linux CLI

```bash
export JAVA_HOME=/path/to/your/jdk
export PATH=$JAVA_HOME/bin:$PATH
```

## macOS CLI

```bash
export JAVA_HOME=/path/to/your/jdk
export PATH=$JAVA_HOME/bin:$PATH
```

---

If successful, check the commands again to verify that your Java SDK is ready for coding. Then, choose your IDE!
