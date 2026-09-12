OOP Practice Sessions
1. Overview
This folder contains two beginner‑level Python programs:

Simple Banking System

Simple Library System

These programs were written as practice exercises for my IT certificate course to learn object‑oriented programming (OOP) and basic software design principles. They model small real‑world systems using classes, objects, attributes, and methods.

2. What’s in this folder
Banking System
A simple program that lets a user:

create an account

deposit money

withdraw money

check their balance

It uses classes like Account, Transaction, and a basic controller to manage actions.

Library System
A small program that lets a user:

add books

register members

borrow and return books

track availability

It uses classes such as Book, Member, and Library.

Each program runs on its own and is designed to show beginner‑level OOP structure.

3. Purpose of the Programs
These programs were part of learning exercises to help practise:

designing classes and methods

applying OOP concepts

using software design principles

organising code into small, clear parts

modelling simple systems

They are prototypes, not full applications.

4. Software Design Principles Used
To keep the code organised and easy to follow, I used common software design principles. These helped shape how the classes were structured and how they interact.

Modularity
Each system is split into small classes:

Banking: Account, Transaction  
Library: Book, Member, Library

This keeps the code tidy and easier to update.

Cohesion
Each class has one job:

Account handles balances

Transaction handles deposits/withdrawals

Book stores book details

Member manages borrowing

Library coordinates everything

This makes the code easier to understand.

Coupling
The classes interact without depending too heavily on each other.
For example, Transaction uses an Account, but doesn’t change how the account works internally.
This makes changes safer and easier.

Abstraction
Methods hide the internal details.
For example, deposit() and borrow_book() handle the logic inside the class so the user only sees the simple interface.

Encapsulation
Important data (like balances or borrowed books) is stored inside the class and only changed through methods.
This protects the data and keeps things consistent.

5. Why These Principles Help
Using these principles made both programs:

easier to read

easier to update

easier to extend later

less likely to break when changes are made

It also helped me understand how OOP structure supports real‑world systems.

6. Program Summaries
Simple Banking System
Features:

create an account

deposit and withdraw

view balance

Shows:

class interaction

state changes

simple transaction logic

Simple Library System
Features:

add books

register members

borrow/return books

track availability

Shows:

object relationships

list management

borrowing rules

7. Reflection
Working on these two small systems helped me understand how OOP and software design principles fit together. Breaking the programs into classes made everything easier to manage, and using principles like modularity, cohesion, and encapsulation helped me keep the code organised. It also made me more confident writing beginner‑level Python programs that follow a clear structure.

8. How to Run
Install Python 3

Download the folder

Run each program using:

Code
python banking_system.py
python library_system.py
9. References
Software Design Principles Resource  
Institute of Data – Software Design Principles: Creating Improved System Designs  
https://www.institutedata.com/nz/blog/software-design-principles-creating-improved-system-designs/

README Writing Resource  
Make a README – A guide to writing clear and effective README files  
https://www.makeareadme.com/
