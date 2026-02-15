# C++ Module 01

## 📝 Overview

This module is designed to help you understand the memory allocation, reference, pointers to members and the usage of the switch statement.

**Key Concepts:**

- Memory allocation (`new`, `delete`)
- References vs Pointers
- Pointers to members
- File streams (`fstream`)
- `switch` statement

## 📂 Exercises

### [Exercise 00: BraiiiiiiinnnzzzZ](./ex00/)

**Goal:** Understand memory allocation.

> Create a `Zombie` class.
> Implement a function `newZombie` that allocates on the heap.
> Implement a function `randomChump` that allocates on the stack.

### [Exercise 01: Moar brainz!](./ex01/)

**Goal:** Allocating multiple objects at once.

> Implement a function `zombieHorde` that allocates `N` Zombie objects in a single allocation.

### [Exercise 02: HI THIS IS BRAIN](./ex02/)

**Goal:** Demystify references.

> Create a program containing:
>
> - A string variable.
> - A pointer to the string.
> - A reference to the string.
> - Display the memory address and value of the string using all three.

### [Exercise 03: Unnecessary violence](./ex03/)

**Goal:** Understand references vs pointers in class members.

> Create a weapon class and two types of human classes (`HumanA` & `HumanB`).
>
> - `HumanA` takes the Weapon in its constructor (reference).
> - `HumanB` may not always have a Weapon (pointer).

### [Exercise 04: Sed is for losers](./ex04/)

**Goal:** File manipulation.

> Create a program that takes a filename and two strings, `s1` and `s2`.
> It should open the file and copy its content into a new file `<filename>.replace`, replacing every occurrence of `s1` with `s2`.
> Usage of `std::string::replace` is forbidden (manual search/replace logic required).

### [Exercise 05: Harl 2.0](./ex05/)

**Goal:** Pointers to member functions.

> Create a `Harl` class that complains a lot.
> It has 4 levels: `DEBUG`, `INFO`, `WARNING`, `ERROR`.
> Use pointers to member functions to dispatch calls based on level string, avoiding a forest of `if/else if`.

## 🛠️ Usage

```bash
cd exXX/
make
./program
```
