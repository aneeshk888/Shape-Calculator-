# 🟦 Shape Calculator (C++ OOP Project)

## 📖 Overview
The **Shape Calculator** is a console-based C++ application that demonstrates advanced **Object-Oriented Programming (OOP)** concepts.  
It provides a menu-driven interface to create, display, and compare different geometric shapes.

## ✨ Features
- Create shapes at runtime:
  - Circle  
  - Rectangle  
  - Square  
  - Triangle  
  - Ellipse  
- Display **area** and **perimeter** of each shape  
- Compare two shapes by **area** using operator overloading  
- Interactive **menu dashboard** for user-friendly navigation  

## 🛠️ Project Requirements
This project highlights the following C++ concepts:
- Classes & Objects  
- Inheritance & Access Specifiers  
- Constructors & Destructors  
- Virtual Functions & Method Overriding  
- Operator Overloading  
- Dynamic Memory Allocation  

You’ll need a working C++ environment such as:
- Compiler: `g++`, `clang++`  
- IDE: Code::Blocks, Visual Studio Code, CLion  

## 🏗️ Implementation Steps
1. **Base Shape Class**  
   - Abstract class with pure virtual functions for `area()`, `perimeter()`, and `display()`.  
   - Virtual destructor for polymorphism.  
   - Overloaded `>` operator to compare shapes by area.  

2. **Derived Shape Classes**  
   - Circle, Rectangle, Square, Triangle, Ellipse.  
   - Each overrides `area()`, `perimeter()`, and `display()` methods.  

3. **Menu-Driven Dashboard**  
   - Options to create shapes, display all shapes, and compare two shapes.  
   - Uses dynamic memory allocation (`new`) and stores shapes in a vector.  

4. **Main Function**  
   - Starts the dashboard loop.  
   - Cleans up allocated memory before exit.  


## 🚀 How to Run

   ```bash
   git clone https://github.com/yourusername/ShapeCalculator.git
   cd ShapeCalculator

g++ main.cpp -o ShapeCalculator


./ShapeCalculator
```

## 🎯 Learning Outcomes
By working on this project, you will:

- Understand polymorphism and virtual functions in C++

- Implement inheritance and operator overloading effectively

- Manage dynamic memory safely

- Build a menu-driven console application



