📚 E-Library Book Project

📌 Overview

The **E-Library Book Project** is a simple digital library management system built in **Python**. It allows users to add books, register members, borrow and return books, and check overdue loans. The system is lightweight, uses a local database, and runs on the command line.

This project helps you understand:

* Database handling with **SQLite**
* CRUD operations (Create, Read, Update, Delete)
* Basic CLI (Command Line Interface) application structure
* Simple real-world library management use case

---
⚙️ Tools Used

* **Python 3.x** → Core programming language
* **SQLite3** (built into Python) → To store books, members, and loan records
* **Datetime module** → For handling borrow/return dates
* **Command Line Interface (CLI)** → Simple text-based interaction

---
✨ Features

✅ **Add Books** – Store book details (title, author, year, copies)
✅ **Register Members** – Add new members with name & email
✅ **Search Books** – Find books by title or author
✅ **Borrow & Return Books** – Manage book availability and due dates
✅ **List Books & Members** – Display all books and members
✅ **Active Loans** – See which books are currently borrowed
✅ **Overdue Loans** – Check books not returned by due date
✅ **SQLite Database** – Data is saved in `elibrary.db` file

---

▶️ How to Run

1. **Install Python**

Make sure Python 3.x is installed. Check with:

```bash
python --version
```

(or `python3 --version` on Linux/Mac)

2. **Download Project**

Save the project file as `elibrary.py` in any folder.

3. **Run Program**

Open terminal (or CMD) in the project folder and run:

```bash
python elibrary.py
```

(or `python3 elibrary.py`)

4. **Use the Menu**

You’ll see a menu like this:

```
=== e-Library ===
1) Add book  2) Register member  3) Search books
4) Borrow book  5) Return book    6) List books
7) List members 8) Active loans   9) Overdue
0) Exit
```

* Choose options by typing the number and pressing Enter.
* Example: Type `1` to add a new book.
  
 5. **Database**

* The system automatically creates a file called **`elibrary.db`** (SQLite database).
* You don’t need to install anything extra.
