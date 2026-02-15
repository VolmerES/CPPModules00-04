# C++ Module 04

## 📝 Overview

This module is designed to help you understand Subtype Polymorphism, abstract classes and interfaces.

**Key Concepts:**

- Subtype Polymorphism
- Abstract Classes
- Pure Virtual Functions (`= 0`)
- Interfaces

## 📂 Exercises

### [Exercise 00: Polymorphism](./ex00/)

**Goal:** Introduction to polymorphism.

> Implement a base class `Animal` and derived classes `Dog` and `Cat`.
>
> - `Animal` has a `makeSound()` function.
> - `Dog` and `Cat` override it.
> - Create a `WrongAnimal` and `WrongCat` to demonstrate what happens without `virtual`.

### [Exercise 01: I don’t want to set the world on fire](./ex01/)

**Goal:** Memory management in polymorphism.

> - Implement a `Brain` class with an array of ideas.
> - `Dog` and `Cat` should have a `Brain*` attribute.
> - Ensure deep copies are made (copy constructor/assignment).
> - Check for memory leaks.

### [Exercise 02: Abstract class](./ex02/)

**Goal:** Abstract classes.

> - Modify `Animal` so it cannot be instantiated (make it abstract).
> - This is done by making at least one function pure virtual (e.g., `makeSound() = 0;`).
> - This prevents creating generic `Animal` objects, enforcing specific types (`Dog`, `Cat`).

## 🛠️ Usage

```bash
cd exXX/
make
./program
```
