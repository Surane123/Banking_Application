# Banking Application

A console application for practicing account operations, Java classes, validation, and exception handling.

## Features

- Deposit positive amounts and show the updated balance.
- Withdraw positive amounts when sufficient funds are available.
- Check the current balance.
- Reject non-numeric, zero, negative, and over-precision amounts.
- Explain insufficient-funds withdrawals without changing the balance.

The account starts at 0.00. BankAccount owns the balance and business rules, BankingApp handles console interaction, and Main starts the program. BigDecimal is used for monetary amounts.

## Files

- BankAccount.java
- BankingApp.java
- InsufficientFundsException.java
- Main.java

## Compile and run

Requires JDK 17 or newer. From the repository root, run:

    javac -d out *.java
    java -cp out banking.Main

No external libraries are required.

## Sample session

    Enter your choice: 1
    Enter deposit amount: 5000
    Deposit successful.
    Current Balance: 5,000.00
    Enter your choice: 2
    Enter withdrawal amount: 1250
    Withdrawal successful.
    Current Balance: 3,750.00

## Author

Surender R. (GitHub: Surane123)
