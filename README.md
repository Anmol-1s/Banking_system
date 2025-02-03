# Banking_system
Banking System project is a Java-based application that uses JDBC with MySQL for database operations. It provides user authentication, account management, and transaction handling functionalities.

Key Features:
User Management:

Registration: Users can create an account.
Login: Authentication system with email and password.
Bank Account Operations:

Open a New Account: If a user doesn't have an account, they can create one.
Retrieve Account Number: Fetches the associated account number.
Transaction Handling:

Debit Money: Withdraws money from the account.
Credit Money: Adds money to the account.
Transfer Money: Transfers funds between accounts.
Check Balance: Displays the current balance.
Database Integration (MySQL)

Uses JDBC for connecting to MySQL.
Credentials are stored securely using environment variables.
Uses Prepared Statements to prevent SQL injection.
Class Structure:
User: Handles user registration & login.
Accounts: Manages account creation & retrieval.
Accounts_manager: Handles transactions (debit, credit, transfer).
Security & Error Handling:
Uses try-catch blocks to handle database and input errors.
Ensures valid user input to avoid crashes.
Secure credentials storage using environment variables instead of hardcoding them.
