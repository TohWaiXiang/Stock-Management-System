# Stock Management System

A Java-based stock management application developed for an appliance store. The project provides both a **JavaFX graphical user interface** and a **console-based version**, allowing users to manage appliance products and stock records.

## Project Overview

The system demonstrates object-oriented programming through an abstract `Product` class and specialised product types. The JavaFX version uses FXML views and controllers to separate the user interface from application logic, while repository classes organise product-related operations.

This repository contains the coursework project package in `uccd2044-assignment.zip`.

## Features

- **User registration** – create an account through the sign-up functionality.
- **Add products** – add appliance products to the stock list.
- **View products** – display the products managed by the system.
- **Adjust stock** – update product stock quantities.
- **Discontinue products** – mark products as discontinued.
- **Two interfaces** – use the JavaFX graphical application or the console-based version.

## Technologies

- **Language:** Java
- **GUI:** JavaFX
- **UI layout:** FXML
- **Programming approach:** Object-Oriented Programming (OOP)

## OOP Concepts Demonstrated

- **Abstraction:** an abstract `Product` class defines the common structure for products.
- **Inheritance:** `Refrigerator`, `TV`, and `HairDryer` are specialised product classes derived from `Product`.
- **Encapsulation:** product data and operations are organised within classes.
- **Separation of responsibilities:** FXML views, controllers, and repository classes help organise the JavaFX application.

## Product Types

| Class | Description |
| --- | --- |
| `Product` | Abstract base class for shared product structure |
| `Refrigerator` | Product type representing refrigerators |
| `TV` | Product type representing televisions |
| `HairDryer` | Product type representing hair dryers |

## Getting Started

### Requirements

- A Java Development Kit (JDK)
- An IDE that supports Java projects, such as IntelliJ IDEA, Eclipse, or NetBeans
- JavaFX libraries/SDK for running the graphical version, if they are not already configured in your IDE

### Get the project files

1. Open the `uccd2044-assignment.zip` file in this repository.
2. Download and extract the archive to your computer.
3. Open the extracted project in your Java IDE.
4. For the JavaFX version, configure the JavaFX SDK or libraries required by the project.
5. Locate the appropriate application entry point in the source code and run the JavaFX or console version.

> **Note:** The exact run configuration depends on the project files and JavaFX setup included in the coursework package.

## Repository Contents

```text
Stock-Management-System/
├── .gitignore
├── README.md
└── uccd2044-assignment.zip
```

The source files are currently kept inside the coursework ZIP archive. A future improvement is to extract and organise the source code directly in the repository so that the code can be browsed on GitHub without downloading the archive.

## Academic Project

This project was developed as part of a university coursework assignment. It provided practical experience with Java, JavaFX, FXML, class design, inheritance, and organising application logic into separate classes.

---

**Author:** Toh Wai Xiang
