# Java Storefront System

A modular Java application simulating a simple online storefront. Developed as part of an Object-Oriented Programming assignment, it supports both **admin** and **customer** operations with a clear separation of concerns via shared utilities and command-based interaction.

## Features

- Admin and Customer interfaces with different functionalities
- Inventory management using a centralized `InventoryManager`
- Shopping cart operations and purchase workflows
- Command design pattern for modular action handling
- Clean object-oriented design with factory and interface patterns

## Project Structure

- `Client/` - User-facing logic (Admin & Customer operations)
- `Common/` - Shared models and utilities
- `Store/` and `Jar/` - Server-related or deployment components
- `makefile` - Compilation instructions
- `README_Assignment_3.txt`, `OOP Assignment-3.pdf` - Assignment documentation

## Getting Started

### Requirements

- Java Development Kit (JDK) 8 or above
- Terminal or command line interface

### Build and Run

1. Navigate to the project root directory.
2. Use the provided `makefile` to compile the project:
   ```bash
   make
   ```
3. Run the application based on the generated class files.

## Documentation

For detailed instructions and design overview, refer to:
- `README_Assignment_3.txt`
- `OOP Assignment-3.pdf`

---

© Aditya Sholapurkar
