# Lesson 09: Methods in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

Methods are one of the most important concepts in C# programming.  
They help you **organize code into reusable blocks**.

Instead of writing the same logic again and again, we use methods.

---

# 2. What is a Method?

A method is a **block of code that performs a specific task**.

Example:
- Adding numbers
- Printing messages
- Calculations
- Validations

---

# 3. Why Methods are Important

Methods help to:
- Reduce code repetition
- Improve readability
- Make debugging easier
- Organize programs professionally

---

# 4. Basic Method Syntax

```csharp id="methodsyntax01"
returnType MethodName()
{
    // code
}
```
# 5. Simple Method Example
```bash
using System;

class Program
{
    static void SayHello()
    {
        Console.WriteLine("Hello C#");
    }

    static void Main()
    {
        SayHello();
    }
}
```
# 6. Methods with Parameters
Parameters allow us to pass values into a method.
```bash
static void Greet(string name)
{
    Console.WriteLine("Hello " + name);
}
Calling Method:
Greet("Daham");
```
# 7. Methods with Return Value
A method can return a value.
```bash
static int Add(int a, int b)
{
    return a + b;
}
Usage:
int result = Add(10, 20);
Console.WriteLine(result);
```
# 8. Void vs Return Methods
| Type   | Meaning               |
| ------ | --------------------- |
| void   | Does not return value |
| return | Returns a value       |

# 9. Method Overloading
Same method name but different parameters.
```bash
static int Add(int a, int b)
{
    return a + b;
}

static double Add(double a, double b)
{
    return a + b;
}
```
# 10. Real World Example
Calculator using methods:
```bash
using System;

class Program
{
    static int Add(int a, int b)
    {
        return a + b;
    }

    static int Multiply(int a, int b)
    {
        return a * b;
    }

    static void Main()
    {
        Console.WriteLine(Add(5, 10));
        Console.WriteLine(Multiply(5, 10));
    }
}
```
# 11. Recursion (Basic Concept)
A method calling itself.
```bash
static void CountDown(int i)
{
    if (i == 0)
        return;

    Console.WriteLine(i);
    CountDown(i - 1);
}
```
# 12. Common Mistakes
- Forgetting return type
- Not calling methods
- Wrong parameters
- Infinite recursion
- Missing brackets
