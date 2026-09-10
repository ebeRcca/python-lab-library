# Week 7 – Object-Oriented Programming (OOP)

This week focuses on the fundamentals of Object-Oriented Programming in Python.  
The exercises introduce classes, objects, attributes, and methods, and show how OOP helps structure programs into clear, reusable components.

## Activity 1 – Simple Banking System

This mini‑project practised basic OOP concepts by modelling a simple banking system using three classes:

### Classes Implemented
- **Account** – stores an account number and balance.
- **Customer** – stores customer details and their associated account.
- **Transaction** – stores transaction information such as amount and type.

### Methods Practised
- `deposit(amount)` – adds money to the account.
- `withdraw(amount)` – removes money if sufficient balance is available.
- `display_balance()` – prints the current balance.

### What I Learned
- How to design classes that represent real‑world objects.
- How methods operate on object data.
- How objects interact (e.g., Customer → Account → Transaction).
- How OOP improves structure compared to procedural code.

## Activity 2 – Simple Library Management System

A second OOP exercise involved building a basic library system using three classes:

### Classes Implemented
- **Book** – stores title, author, and availability status.
- **Member** – stores member name and a list of borrowed books.
- **Library** – manages collections of books and members, and handles borrowing and returning.

### Methods Practised
- `add_book()` – adds a book to the library.
- `borrow_book()` – marks a book as borrowed and assigns it to a member.
- `return_book()` – marks a book as available again.
- `display_books()` – lists all books with their availability status.

### Peer Review
As part of the lab session:
- I reviewed a classmate’s code for clarity and correctness.
- I checked whether the OOP structure was used properly.
- I provided improvement suggestions and made small updates based on feedback.

## Software Design Principles Demonstrated

- **Modularity** – each class handles one part of the system (books, members, accounts, transactions).
- **Cohesion** – methods perform single, clear tasks such as depositing money or borrowing a book.
- **Reusability** – classes and methods can be reused or extended in future exercises.
- **Encapsulation** – data (like balance or availability) is stored inside objects and accessed through methods.
- **Readability** – clear naming and structure make the code easy to understand and maintain.

This week strengthened my understanding of how OOP helps organise code into logical, reusable components.

