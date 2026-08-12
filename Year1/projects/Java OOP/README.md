# E-Commerce Product Inventory System (Java OOP)

A simple Java console application demonstrating core **Object-Oriented Programming (OOP)** principles, specifically **Inheritance (`extends`)**, **Constructor Chaining (`super`)**, and **Method Overriding**.

## Features
* **Parent Class (`Product`)**: Manages core attributes shared by all products (`name`, `price`, `productId`) and provides basic display logic and getters.
* **Child Class (`Book`)**: Extends `Product` with an additional `author` attribute and overrides `displayInfo()`.
* **Child Class (`Electronics`)**: Extends `Product` with an additional `warrantyMonths` attribute and overrides `displayInfo()`.
* **Polymorphic / Code Reuse**: Utilizes `super()` to initialize parent variables and `super.displayInfo()` to avoid code duplication.

## Technologies Used
* Java
* Object-Oriented Programming (OOP)

## How to Run
1. Clone the repository.
2. Compile the Java files:
   ```bash
   javac Main.java
