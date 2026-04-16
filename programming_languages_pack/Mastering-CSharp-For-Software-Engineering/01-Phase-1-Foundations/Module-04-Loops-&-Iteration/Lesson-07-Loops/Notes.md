# Lesson 07: Loops in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

In programming, loops are used to **repeat a block of code multiple times** until a condition becomes false.

Instead of writing the same code again and again, we use loops to automate repetition.

---

# 2. What is a Loop?

A loop is a control structure that allows a program to execute a block of code repeatedly based on a condition.

---

# 3. Types of Loops in C#

C# provides three main types of loops:

- for loop  
- while loop  
- do-while loop  

---

# 4. for Loop

## Syntax

```csharp id="for01"
for (initialization; condition; increment/decrement)
{
    // code block
}
```
**Example**
```bash
for (int i = 1; i <= 5; i++)
{
    Console.WriteLine(i);
}
```
**Explanation**
- Initialization: starts the loop
- Condition: checks before each iteration
- Increment: updates value after each loop

# 5. while Loop
## Syntax
```bash
while (condition)
{
    // code block
}
```
**Example**
```bash
int i = 1;

while (i <= 5)
{
    Console.WriteLine(i);
    i++;
}
```
**Explanation**
- Condition is checked first
- If true → loop runs
- If false → loop stops

# 6. do-while Loop
## Syntax
```bash
do
{
    // code block
}
while (condition);
```
**Example**
```bash
int i = 1;

do
{
    Console.WriteLine(i);
    i++;
}
while (i <= 5);
```
**Key Feature**
- Executes at least once, even if condition is false

# 7. break Statement
Used to exit the loop immediately
```bash
for (int i = 1; i <= 10; i++)
{
    if (i == 5)
        break;

    Console.WriteLine(i);
}
```
# 8. continue Statement
Used to skip current iteration
```bash
for (int i = 1; i <= 10; i++)
{
    if (i == 5)
        continue;

    Console.WriteLine(i);
}
```
# 9. Nested Loops
A loop inside another loop.
```bash
for (int i = 1; i <= 3; i++)
{
    for (int j = 1; j <= 3; j++)
    {
        Console.WriteLine(i + " " + j);
    }
}
```
# 10. Real World Example
Multiplication Table
```bash
int number = 5;

for (int i = 1; i <= 10; i++)
{
    Console.WriteLine(number + " x " + i + " = " + (number * i));
}
```
# 11. Common Mistakes
- Forgetting loop increment
- Creating infinite loops
- Wrong condition logic
- Using wrong loop type