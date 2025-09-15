# library-manager# Library Management System (Python + MySQL)

The **Library Management System** is a Python-based project that helps manage the daily operations of a library such as adding and updating books, keeping track of borrowers, issuing and returning books, and calculating fines. It uses **MySQL** as the database for storing and managing all the records.

---


### 1. Home Menu  
This is the main menu of the system where users can select different operations.  


---

### 2. Add New Book  
Form to add a new book with details like title, author, ISBN, and quantity.  


---

### 3. Borrower Management  
Interface for adding and updating borrower details.  


### 4. Borrow & Return Books  
Borrow books by entering borrower ID and book ID. System tracks due dates automatically.  
![Borrow Screenshot](images/borrow.png)

---

### 5. Fine Calculation  
When a book is returned late, the system calculates the fine and updates the database.  
![Fine Screenshot](images/fine.png)

---

## ⚙️ Features
- Manage books (add, update, delete)  
- Manage borrowers and membership details  
- Borrow and return books with due date tracking  
- Calculate fines for late returns  
- Search books by title, author, or genre  
- Generate simple reports  

---

## 💻 Technologies Used
- Python 3  
- MySQL  
- MySQL Connector (Python library)  
- (Optional) Tkinter/PyQt for GUI  

---

## 🚀 How to Run
1. Clone the repository  
2. Install required Python packages  
3. Set up the MySQL database  
4. Update DB credentials in the code  
5. Run `python main.py`  
