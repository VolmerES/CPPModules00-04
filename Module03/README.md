# C++ Module 03

## 📝 Overview

This module is designed to help you understand Inheritance in C++.

**Key Concepts:**

- Inheritance (`public`, `protected`, `private`)
- Derived classes
- Diamond problem (Virtual inheritance is Module 04/Concept, but relevant)
- Construction/Destruction chaining

## 📂 Exercises

### [Exercise 00: Aaaaand... OPEN!](./ex00/)

**Goal:** Create your first class.

> Implement a class `ClapTrap` that has:
>
> - Name
> - Hit points (10)
> - Energy points (10)
> - Attack damage (0)
> - Functions: `attack`, `takeDamage`, `beRepaired`.

### [Exercise 01: Serena, my love!](./ex01/)

**Goal:** Basic inheritance.

> Create a class `ScavTrap` that inherits from `ClapTrap`.
>
> - Different default values (HP: 100, Energy: 50, Attack: 20).
> - Specific function: `guardGate`.
> - Special message in constructor/destructor to verify chaining.

### [Exercise 02: Repetitive work](./ex02/)

**Goal:** More inheritance.

> Create a class `FragTrap` that inherits from `ClapTrap`.
>
> - Different default values (HP: 100, Energy: 100, Attack: 30).
> - Specific function: `highFivesGuys`.

## 🛠️ Usage

```bash
cd exXX/
make
./program
```
