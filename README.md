# Python Abstraction

## Explanation

Abstraction is an Object-Oriented Programming concept that hides implementation details and exposes only the essential functionality.

Python provides the `abc` module to create abstract classes and abstract methods.

## Problem Statement

Write a Python program using an abstract `Shape` class and implement the `area()` method in different child classes.

## Features

* Demonstrates abstraction
* Uses the `abc` module
* Uses an abstract class
* Uses an abstract method
* Implements different shapes
* Demonstrates method overriding

## How It Works

1. The `Shape` class is created as an abstract class.
2. The `area()` method is declared as an abstract method.
3. `Circle` and `Rectangle` inherit from `Shape`.
4. Each child class provides its own implementation of `area()`.
5. Objects are created for both shapes.
6. Their areas are calculated and displayed.

## Technologies Used

* Python 3
* Object-Oriented Programming
* `abc` module
* Abstract Classes
* Abstract Methods

## Program Flow

Start → Create Abstract Class → Define Abstract Method → Create Child Classes → Implement Method → Create Objects → Calculate Areas → End

## Sample Input

```text id="r3n8vx"
No user input required.
```

## Sample Output

```text id="c7m2qa"
Circle Area: 78.54
Rectangle Area: 50
```

## Key Learning

* Abstraction hides unnecessary implementation details.
* Abstract classes provide a common structure.
* `ABC` is used to create abstract base classes.
* `@abstractmethod` defines methods that child classes must implement.
* Abstract classes cannot be instantiated directly.

## File Location

```text id="k5x9wp"
Python-Abstraction/abstraction.py
```

## Repository Structure

```text id="v2q6ms"
Python-Abstraction/
│
├── abstraction.py
└── README.md
```

## Author

V.Harini
