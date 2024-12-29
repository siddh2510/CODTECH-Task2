# CODTECH-Task2
NAME:SIDDHI JAMDADE 
COMPANY:CODTECH IT SOLUTIONS
ID DOMAIN:JAVA PROGRAMMING 
DURATION:DEC TO JAN2024 
MENTOR:SRAVANI GOUNI

Project Overview: Online Banking System
![Screenshot 2024-12-25 004005](https://github.com/user-attachments/assets/cb81cdb7-607d-4b7b-8793-1c22588f802f)


Main Features:
Account Creation:

Users can create new accounts with a unique account number and account holder's name. The account balance is initially set to 0.
Deposit Money:

Users can deposit money into their accounts. The system checks that the deposit amount is positive before updating the balance.
Withdraw Money:

Users can withdraw money from their accounts, provided they have sufficient funds. If the withdrawal amount exceeds the available balance, the system will notify the user of insufficient funds.
Transfer Money:

Users can transfer money between their accounts. The system checks for valid accounts and ensures the sender has enough balance before completing the transfer.
View Transaction History:

Users can view the transaction history for their accounts, including deposits, withdrawals, and transfers. The history is stored in an ArrayList for each account.
Update Personal Information:

Users can update their account holder's name.
Classes & Methods:
Account Class:

Attributes:
accountHolder: Name of the account holder.
accountNumber: Unique identifier for the account.
balance: Current balance in the account.
transactionHistory: List of transaction strings.
Methods:
deposit(double amount): Deposits money into the account.
withdraw(double amount): Withdraws money from the account, ensuring sufficient balance.
transfer(Account targetAccount, double amount): Transfers money from the current account to another account.
viewTransactionHistory(): Displays the transaction history.
updateAccountHolder(String newAccountHolder): Updates the account holder's name.
addTransactionHistory(String transaction): Adds a transaction to the history.
Main Class:

Contains the main method which is the entry point for the program.
Provides a menu-driven interface with options for creating accounts, depositing money, withdrawing money, transferring funds, viewing transaction history, and updating personal information.
Handles input and output via the Scanner class, guiding users through each operation and validating user input.
User Interface:
A text-based menu offers users a set of choices.
Input is validated for numerical entries, and invalid inputs are handled appropriately.
Each operation prompts the user for specific details (e.g., account number, deposit amount), and results are displayed after each action.
Key Data Structures:
ArrayList<Account> accounts: Stores all the accounts created by users.
ArrayList<String> transactionHistory: Maintains a record of each account's transactions.
Error Handling:
The program checks for valid inputs such as positive deposit/withdrawal amounts.
It ensures that a transfer can only happen if the sender has enough funds and both the sender and recipient accounts exist.
Usage:
This system simulates a basic banking environment and is useful for understanding object-oriented programming concepts such as classes, objects, and methods in Java. It also demonstrates how to manage user input, perform operations on data, and handle simple financial transactions programmatically
