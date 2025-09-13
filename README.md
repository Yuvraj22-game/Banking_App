# Banking_App
Banking Application – Account Management
📌 Project Overview

This project is a simple Banking Application written in Java. It allows users to manage their bank accounts through operations such as:

Creating a new account

Depositing money

Withdrawing money

Viewing account details

Updating contact information

The program demonstrates the use of Java classes, objects, arrays, control structures, input handling (Scanner), and string manipulation.

🎯 Objectives

Apply the basics of Java programming including data types, operators, and control structures.

Implement basic I/O operations using the Scanner class.

Manage multiple accounts using arrays.

Handle string input and updates (names, emails, phone numbers).

Gain practical experience with encapsulation, modular design, and object-oriented principles.

🏗️ Implementation Details
1. Account Class

Attributes:

accountNumber (auto-generated unique ID)

accountHolderName

balance

email

phoneNumber

Methods:

deposit(double amount) → Adds funds (validates positive amount).

withdraw(double amount) → Deducts funds (checks balance & positive amount).

displayAccountDetails() → Prints account information.

updateContactDetails(String email, String phoneNumber) → Updates contact info.

2. UserInterface Class

Attributes:

Array of Account objects (max 100 accounts).

Scanner object for user input.

Methods:

createAccount() → Creates a new account and stores it in the array.

performDeposit() → Handles deposit operations.

performWithdrawal() → Handles withdrawal operations.

showAccountDetails() → Displays account details by account number.

updateContact() → Updates email and phone number.

mainMenu() → Displays the menu and handles user choices.

📂 File Structure
BankingApp/
│── UserInterface.java   # Main program entry point
│── Account.java         # Account class (inside same file here)
│── README.md            # Project documentation

▶️ How to Run
Compile the program:

javac UserInterface.java


Run the program:

java UserInterface


Sample Menu:

Welcome to the Banking Application!
1. Create a new account
2. Deposit money
3. Withdraw money
4. View account details
5. Update contact details
6. Exit
Enter your choice:

!!!!THANK YOU!!!!
