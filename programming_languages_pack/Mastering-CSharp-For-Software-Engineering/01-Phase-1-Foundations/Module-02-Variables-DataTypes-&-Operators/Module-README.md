# Module 02: Variables, Data Types & Operators
## Mastering C# for Software Engineering (Beginner to Professional)

---

# Overview

In this module, you will learn the **fundamental building blocks of programming in C#**:

- Variables (storing data)
- Data Types (types of data)
- Operators (performing calculations and logic)

These concepts are essential for writing any C# program.

---

# Learning Objectives

By the end of this module, you will be able to:

- Understand what variables are and how to use them
- Use different data types in C#
- Perform calculations using operators
- Convert data between types
- Build simple logic-based programs

---

# Lesson 1: Variables in C#

## What is a Variable?

A variable is a **container used to store data** in a program.

Think of it like a box:
- You can put data inside it
- You can change it anytime
- It has a name

---

## Syntax of Variable

```csharp id="var01"
dataType variableName = value;
```

Example
```bash
int age = 20;
string name = "Daham";
```

**Rules for Naming Variables**
- Must start with a letter or underscore
- Cannot use keywords (like int, class)
- Should be meaningful
- Case-sensitive

**Example (Good vs Bad Naming)**

Good:
```bash
int studentAge = 18;
```
Bad:
```bash
int a = 18;
```