# Lesson 01: What is C#

## Full Study Notes (Beginner to Professional Level)

---

# 1. Introduction

C# (pronounced **C-Sharp**) is a modern programming language developed by Microsoft.  
It is one of the most powerful and widely used languages in the software industry today.

C# is mainly used with the **.NET platform** to build professional software systems.

---

# 2. What is C#

C# is a:

- Object-Oriented Programming (OOP) language  
- General-purpose programming language  
- Type-safe language  
- Modern and scalable language  

It allows developers to build:

- Desktop applications  
- Web applications  
- APIs (Backend systems)  
- Cloud services  
- Games (Unity)  

---

# 3. Why C# Was Created

Microsoft created C# to:

- Replace older languages like C++ complexity in business applications  
- Provide a modern, safe, and structured programming language  
- Support rapid application development  
- Work perfectly with .NET framework  

---

# 4. Features of C#

## 4.1 Object-Oriented Programming (OOP)

C# is fully based on OOP principles:

- Classes and Objects  
- Encapsulation  
- Inheritance  
- Polymorphism  
- Abstraction  

---

## 4.2 Strongly Typed Language

Every variable must have a defined type:

- int → numbers  
- string → text  
- bool → true/false  

This reduces errors in large applications.

---

## 4.3 Automatic Memory Management

C# uses a Garbage Collector:

- Automatically removes unused memory  
- Prevents memory leaks  
- Improves performance  

---

## 4.4 Cross-Platform Support

With modern .NET:

- Windows  
- Linux  
- macOS  

---

## 4.5 High Performance

C# is compiled and optimized through the .NET runtime, making it fast and reliable.

---

# 5. Where C# is Used in Real Industry

## 5.1 Enterprise Applications

- Banking systems  
- Hospital systems  
- HR management systems  
- Inventory systems  

---

## 5.2 Web Development (ASP.NET Core)

- E-commerce websites  
- Booking systems  
- Admin dashboards  
- API backends  

---

## 5.3 Game Development (Unity)

- Mobile games  
- PC games  
- 2D and 3D games  

---

## 5.4 Cloud Applications (Microsoft Azure)

- Scalable web APIs  
- Cloud services  
- Microservices  

---

## 5.5 Desktop Applications

- POS systems  
- Accounting software  
- Office tools  

---

# 6. How C# Works (Execution Flow)

When you write C# code:

1. You write code in `.cs` file  
2. Compiler converts code into Intermediate Language (IL)  
3. .NET Runtime executes the code using CLR  
4. Output is displayed  

---

# 7. Key Components of .NET

## CLR (Common Language Runtime)
- Executes C# programs  
- Manages memory  

## BCL (Base Class Library)
- Pre-built functions and classes  

## ASP.NET Core
- Web development framework  

## Entity Framework Core
- Database management tool  

---

# 8. Simple C# Program

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello World");
    }
}