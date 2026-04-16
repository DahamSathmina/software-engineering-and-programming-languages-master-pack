# Lesson 08: Arrays & Foreach in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

In programming, we often need to store multiple values of the same type.

Instead of creating many variables, we use:
- Arrays
- Foreach loops

These help us store and process data efficiently.

---

# 2. What is an Array?

An array is a **collection of multiple values stored in a single variable**.

Example:
- Student marks
- Product prices
- Names list

---

# 3. Why Use Arrays?

Without arrays:
```csharp
int a = 10;
int b = 20;
int c = 30;
```
With arrays:
```bash
int[] numbers = {10, 20, 30};
```
# 4. Array Syntax
```bash
dataType[] arrayName = new dataType[size];
```
# 5. Example of Array
```bash
int[] numbers = {10, 20, 30, 40, 50};
```
# 6. Accessing Array Elements
Array index starts from 0.
```bash
int[] numbers = {10, 20, 30};

Console.WriteLine(numbers[0]); // 10
Console.WriteLine(numbers[1]); // 20
Console.WriteLine(numbers[2]); // 30
```
# 7. Updating Array Values
```bash
int[] numbers = {10, 20, 30};

numbers[1] = 99;

Console.WriteLine(numbers[1]);
```
# 8. Looping Through Arrays (for loop)
```bash
int[] numbers = {10, 20, 30, 40};

for (int i = 0; i < numbers.Length; i++)
{
    Console.WriteLine(numbers[i]);
}
```
# 9. Foreach Loop
What is Foreach?
Foreach is used to iterate through collections easily.

## Syntax
```bash
foreach (dataType item in array)
{
    // code
}
```
Example
```bash
int[] numbers = {10, 20, 30, 40};

foreach (int num in numbers)
{
    Console.WriteLine(num);
}
```
# 10. Difference: for vs foreach
| for loop            | foreach loop    |
| ------------------- | --------------- |
| Uses index          | No index needed |
| More control        | Simpler syntax  |
| Can modify elements | Read-only usage |

# 11. Real World Example
Student Marks System:
```bash
int[] marks = {75, 80, 90, 60, 85};

int total = 0;

foreach (int mark in marks)
{
    total += mark;
}

Console.WriteLine("Total Marks: " + total);
```
# 12. Common Mistakes
- Accessing wrong index
- Going out of array bounds
- Forgetting .Length
- Using wrong data type