# Zoo Management – OOP Final Project in Java

##  Overview
This project was developed as part of an Object-Oriented Programming (OOP) course in Java.  
It simulates a **Zoo Management System**, demonstrating advanced OOP concepts such as inheritance, abstraction, interfaces, polymorphism, enumerations, and custom comparators.

The system models different types of animals (cats, lions, penguins, eagles, fish, etc.) and provides various functionalities like sorting, feeding, and handling exceptions.

---

##  Features
- **Abstract Classes & Inheritance** – Base classes for animals, extended by specific species.  
- **Interfaces** – Multiple interfaces for defining animal behaviors and data structures.  
- **Enums** – Used for animal types, colors, and body signatures.  
- **Custom Comparators** – To sort animals by attributes such as age, name, speed, and altitude.  
- **Data Structures** – Implementation of Binary Trees and Linked Lists for animal collections.  
- **Exception Handling** – Custom exceptions to handle invalid zoo operations.  
- **Zoo Application** – Main entry point to run simulations and interact with the zoo.

---

##  Project Structure

src/
├── abstract_classes/ # Abstract base classes (AnimalAbstract, FishAbstract, etc.)
├── animals/ # Implementations of animals (Cat, Lion, Penguin, etc.)
├── comparators/ # Custom comparators for sorting
├── enums/ # Enums for attributes like fish color, eagle types, etc.
├── interfaces/ # Interfaces for animal behaviors & collections
├── sorting_strategics/ # Data structures (Binary Tree, Linked List)
└── zoo/ # Core zoo logic, exceptions, and main application

---

##  How to Run
1. Import the project into **Eclipse** or **IntelliJ IDEA**.  
2. Ensure JDK 8 or higher is installed.  
3. Run the `ZooApplication.java` file located in the `zoo` package.  

---

##  Learning Outcomes
This project demonstrates:
- Strong understanding of **OOP principles** in Java.  
- Working with **abstraction, polymorphism, and inheritance**.  
- Practical use of **enums, interfaces, and generics**.  
- Implementation of **custom comparators** and **data structures**.  

---

##  Notes
- The `bin/` folder and IDE configuration files are excluded (using `.gitignore`).  
- Only source files (`src/`) are included in this repository.
