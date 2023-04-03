# Vending Machine for Books Using OOP

In this overview, we will describe how to design a vending machine for books using object-oriented programming (OOP) in Java. We'll focus on the main components and their interactions.
  
## Design Overview
Create a Book class to represent a book with attributes such as title, author, price, and stock. It can have methods for accessing and updating these attributes.
Create a VendingMachine class to manage the inventory of books, user balance, and purchase transactions.
Implement methods in the VendingMachine class for adding books, checking the stock, depositing money, and purchasing books.

## VendingMachine Class

The VendingMachine class manages the inventory of books, user balance, and purchase transactions. It should have methods for:

+	Adding a book to the inventory.
+	Checking the stock of a specific book.
+	Depositing money to the user's balance.
+	Purchasing a book, updating the stock, and deducting the price from the user's balance.
+	Displaying available books.

## VendingMachine Class Methods
addBook (Book book) Adds a book to the inventory.

checkStock(String title) Returns the stock of a specific book.

depositMoney(double amount): Adds money to user’s balance

purchaseBook(String title): Purchases a book updating the stock and deducting the price from the user’s balance

displayBooks(): Displays the available books in the inventory.

