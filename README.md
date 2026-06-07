# OOP in C++

This repository demonstrates core Object-Oriented Programming (OOP) concepts in C++ using simple example programs.

## Files and Concepts

- `class_object.cpp`
  - Demonstrates a basic class with public member variables and a member function.
  - Shows how to create an object and call a method.

- `constructors.cpp`
  - Demonstrates a constructor to initialize object state.
  - Uses a `Phone` class with `brand`, `model`, and `price` fields.

- `encapsulation.cpp`
  - Demonstrates encapsulation with private data members and public getter/setter methods.
  - Uses a `Student` class to protect internal data and provide controlled access.

- `inheritance.cpp`
  - Demonstrates class inheritance.
  - Defines `Phone` as a base class, `Smartphone` as a derived class, and `IPhone` as a further derived class.
  - Shows how derived classes extend base class behavior.

- `polymorphism.cpp`
  - Demonstrates runtime polymorphism using virtual functions.
  - Uses an `Animal` base class and derived classes `Dog` and `Cat`.
  - Calls overridden methods through base-class pointers.

## How to Compile and Run

Use a C++ compiler such as `g++`.

Example commands:

```bash
# Compile a file
g++ class_object.cpp -o class_object

# Run the executable
./class_object
```

Repeat for each example file:

```bash
g++ constructors.cpp -o constructors
./constructors
```

## Notes

- The examples use `#include <bits/stdc++.h>` and `std::cout` for simplicity.
- This repository is intended for learning and exploring basic OOP patterns in C++.
- The `output/` folder is present in the workspace and may contain generated or compiled outputs.
