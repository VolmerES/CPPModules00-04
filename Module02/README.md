# C++ Module 02

## 📝 Overview

This module is designed to help you understand ad-hoc polymorphism, operator overloading and the orthodox canonical class form.

**Key Concepts:**

- Ad-hoc Polymorphism
- Operator Overloading (`operator+`, `operator=`, etc.)
- Orthodox Canonical Form
- Floating-point representations (Fixed-point numbers)

## 📂 Exercises

### [Exercise 00: My First Class in Orthodox Canonical Form](./ex00/)

**Goal:** Create a class representing a fixed-point number.

> Implement a class `Fixed` following the Orthodox Canonical Form:
>
> - Default constructor
> - Copy constructor
> - Copy assignment operator
> - Destructor
>
> The class stores the raw value of the fixed-point number.

### [Exercise 01: Towards a more useful fixed-point number class](./ex01/)

**Goal:** Add functionality to convert to/from integers and floats.

> Extend the `Fixed` class with:
>
> - Constructors taking `int` and `float`.
> - Methods `toInt()` and `toFloat()`.
> - Overload the `<<` stream insertion operator.

### [Exercise 02: Now we’re talking](./ex02/)

**Goal:** Full operator overloading.

> Overload the following operators for the `Fixed` class:
>
> - Comparison: `>`, `<`, `>=`, `<=`, `==`, `!=`
> - Arithmetic: `+`, `-`, `*`, `/`
> - Increment/Decrement: `++`, `--` (pre and post)
> - Static member functions `min` and `max`.

## 🛠️ Usage

```bash
cd exXX/
make
./program
```
