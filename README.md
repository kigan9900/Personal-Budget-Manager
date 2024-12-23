# Project: Personal Budget Manager
# Description:
The Personal Budget Manager is a desktop application built in Python using CustomTkinter for the graphical user interface (GUI), SQLite for the database, and Matplotlib for data visualization. The application is designed to help individuals manage their personal finances by allowing them to track income, expenses, and savings goals. Users can add, edit, and delete transactions, view visual spending summaries, and export transaction data to CSV files.

# Features:
# Transaction Management:

Add Transactions: Users can input income and expenses with details like amount, category (e.g., Food, Rent, Utilities), and notes.
Edit Transactions: Users can modify existing transactions, allowing for flexibility in case of data entry errors or changes.
Delete Transactions: Users can delete any selected transaction from the list.
Data Storage:

Transactions are stored in an SQLite database, providing a simple and efficient way to persist data.
Spending Summary:

# Visualization:
The application provides a pie chart that visualizes spending breakdown by category (e.g., how much is spent on food, rent, etc.).
Category Totals: The application can display the total amount spent in each category.
Exporting Data:

# CSV Export:
Users can export all transaction data into a CSV file, which can be used for further analysis or record-keeping.
User Interface:

The application utilizes CustomTkinter for a modern, responsive, and easy-to-use interface.
It supports light/dark mode for user customization and has a clean, professional look.
Responsive Layout:

The user interface is designed to be responsive and intuitive, with input fields for adding new transactions and a table to view existing ones.
Technologies Used:
Python: The programming language used to develop the app.
CustomTkinter: A modern GUI library that extends the standard Tkinter for improved aesthetics and functionality.
SQLite: A lightweight database engine for storing transaction data locally.
Matplotlib: A plotting library to visualize spending summaries in the form of pie charts.
CSV: To export transaction data in a standard format that can be opened in spreadsheet software like Excel.
# Usage:
Add Transactions: Input income or expense details and save them to the database.
Edit/Delete Transactions: Modify or remove entries as needed.
View Spending Breakdown: Check visual spending summaries by category.
Export Data: Save the transaction history as a CSV file for reporting or analysis.
