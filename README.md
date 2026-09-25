# Library Management System

## Project Description

This project is a simple library management system written in Python. It demonstrates object-oriented programming, modular programming, functions, parameters, and user interaction through a terminal menu.

The program allows users to:

- Add new books
- List all books
- Find books by title or author
- Exit the program

## Files

### book.py

Contains the `Book` class. Each Book object contains a title, author, and ISBN.

The class includes:

- `__str__()` for displaying book information
- `get_details()` for returning book information as a dictionary

### library_manager.py

Contains the main program and functions used to manage the library.

The functions are:

- `add_book(library)`
- `list_books(library)`
- `find_book(library, query)`
- `main()`

## How to Run

Make sure Python 3 is installed.

Open a terminal in the project folder and run:

```bash
python3 library_manager.py
