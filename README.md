# 📚 Library Management System (OOP)

## 📖 Project Overview
This project is a Python-based system designed to manage library operations using **Object-Oriented Programming (OOP)**. It simulates the real-world relationships between books, library inventory, and members, allowing for efficient tracking of borrowing and returning processes.

---

## 📂 System Architecture
The project is built around three core classes that interact to manage the library's workflow:

### 1. 📖 The Book Class
Represents individual titles within the library.
* **Attributes:** Title, Author, ISBN, and Available Copies.
* **Purpose:** Acts as the data blueprint for every item in the collection.

### 2. 🏛️ The Library Class
Acts as the central management system.
* **Add/Remove:** Logic to update the library's catalog.
* **Search:** A search algorithm to locate books by title within the collection.

### 3. 👤 The Member Class
Represents the users of the library.
* **Borrowing:** Logic to add a book title to a member's personal list.
* **Returning:** Logic to remove a book from the member's list and check it back into the system.



---

## 🛠️ Key Programming Concepts
* **Class & Object Creation:** Defining blueprints for real-world entities.
* **List Management:** Using Python lists to store and manipulate collections of objects.
* **Method Interaction:** Demonstrating how a `Member` method can interact with `Library` data.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Programming Paradigm:** Object-Oriented Programming (OOP)

---

## 🚀 How to Use
1. Run the `Library Management System.ipynb` notebook.
2. The script initializes a library object (`l1`).
3. You can use `l1.add_book("Title")` to expand the collection or `l1.search_book("Title")` to verify availability.
4. Member objects can be created to simulate the borrowing and returning lifecycle.

---
