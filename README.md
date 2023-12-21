# Simple-Bank-Management-System
This program is a basic implementation of a bank management system. It allows users to perform various banking operations, such as adding and deleting accounts, depositing and withdrawing money, and modifying customer passwords. The system maintains three main dictionaries:

Compte: To store accounts and their balances,
Client: To store customer numbers and passwords,
ClientCompte: To map account numbers to customer numbers.
The program consists of two main menus:

Bank Officer Menu: This menu provides options for a bank officer to add or delete accounts.
Bank Customer Menu: This menu allows bank customers to change their passwords, deposit money, and withdraw money.
The main program loop continuously prompts the user to choose between these two menus or to exit the program. The account creation process involves generating random account numbers and passwords, and each account is associated with a unique customer number.

The system ensures data integrity by updating all relevant dictionaries when performing actions such as adding or deleting an account. Overall, this simple bank management system provides a foundation for basic banking operations.
