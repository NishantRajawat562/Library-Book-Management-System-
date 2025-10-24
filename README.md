# Library Book Management System
### Assignment 2 – Data Structures (ENCS205)

This project is a console-based Library Book Management System made using Singly Linked List and Stack data structures.  
It is part of Assignment 2 for the course Data Structures (ENCS205), Semester 3 (B.Tech CSE).

---

## Project Overview
The Library Book Management System helps manage book records in a library.  
It allows inserting, deleting, searching, issuing, returning, and undoing recent transactions.

The project mainly demonstrates:
- Use of Linked List for dynamic data storage of books.
- Use of Stack for implementing the Undo functionality.
- Basic menu-driven program using Python.

---

## Features

### Book Management (Using Linked List)
- Add a new book  
- Delete an existing book  
- Search a book by ID  
- Display all books  

### Transaction Management (Using Stack)
- Issue a book  
- Return a book  
- Undo last transaction (Issue or Return)  
- View all recent transactions  

---

## Data Structures Used

| Data Structure | Purpose |
|----------------|----------|
| Singly Linked List | To store and manage book records dynamically |
| Stack | To record issue/return operations and allow undo |

---

## Book Record Structure
Each book node contains:

| Attribute | Description |
|------------|--------------|
| BookID | Unique integer ID |
| BookTitle | Title of the book |
| AuthorName | Name of the author |
| Status | Available / Issued |

---

## How to Run the Project

### Step 1: Clone the Repository
git clone https://github.com/your-username/Library-Book-Management-System.git

### Step 2: Open the Folder

Open the project folder in VS Code or any Python IDE.

### Step 3: Run the Python File
python library_management.py

## Menu Options

When you run the program, you will see:

===== Library Book Management System =====
1. Insert Book
2. Delete Book
3. Search Book
4. Display All Books
5. Issue Book
6. Return Book
7. Undo Last Transaction
8. View Transactions
9. Exit


Choose the number for the operation you want to perform.


## License

This project is licensed under the MIT License .
