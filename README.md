# Abstraction Template

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/danielcregg/abstraction-template?style=flat-square)

A Java programming exercise template for learning **abstraction** in object-oriented programming. This repository provides a starter `Main.java` file with guided exercises covering abstract classes, concrete subclasses, constructors, and method implementation.

## Description

In object-oriented programming, abstraction is the process of hiding implementation details from the user while exposing only the essential functionality. This template walks students through creating abstract classes, extending them with concrete subclasses, and implementing abstract methods.

## Prerequisites

- Java Development Kit (JDK) 11 or higher
- A Java IDE or text editor (VS Code with Java Extension Pack recommended)
- Alternatively, use [Gitpod](https://gitpod.io) for a cloud-based development environment

## Getting Started

### Option 1: Gitpod (Recommended)

Prefix the repository URL with `https://gitpod.io/#` to open in a pre-configured cloud IDE:

```
https://gitpod.io/#https://github.com/danielcregg/abstraction-template
```

### Option 2: Local Setup

```bash
git clone https://github.com/danielcregg/abstraction-template.git
cd abstraction-template
javac Main.java
java Main
```

## Exercises

### Exercise 1: Abstract Class Basics

1. Create an abstract class called `AbstractClass`
2. Add an instance variable called `age`
3. Add a constructor with one input parameter that sets `age`
4. Write a getter and setter for the `age` variable
5. Add an abstract method called `returnPi()`
6. Create a concrete class called `AbstractClassDriver`
7. Try to instantiate an object of type `AbstractClass` inside `AbstractClassDriver` -- what happens?
8. Create a concrete class called `AbstractSubClass` that extends `AbstractClass`
9. Add a constructor that sets the `age` variable in the super class
10. Implement the `returnPi()` method to return `3.14`
11. Create a driver class called `AbstractClassDriver` that calls the methods inside `AbstractSubClass`

### Exercise 2: Employee Hierarchy

1. Create an abstract class called `Employee` with `name`, `address`, `age`, and `salary` variables
2. Create a constructor that sets the instance variables
3. Add an abstract method called `computePay()`
4. Create an `Engineer` class that extends `Employee` and implements `computePay()` to return `salary / 12`
5. Create a `Manager` class that extends `Employee` with a `bonus` variable
6. Implement `computePay()` for `Manager` to return `(salary + bonus) / 12`
7. Create a driver class to test all methods

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
