Bank Management Application (C++)

A console-based Bank Management Application built in C++, designed to simulate core banking operations using object-oriented programming and file handling.

Overview

This project allows users to open new bank accounts, log in securely with an account number and PIN, and perform core banking operations. All customer data is persistently stored in a local file (accounts.dat).

Features


Open New Account — Auto-generated account number, name, PIN, and initial deposit
Secure Login — Account number + PIN-based authentication
Deposit — Add funds to an account
Withdraw — Withdraw funds with insufficient-balance protection
Balance Check — View current account details and balance
Persistent Storage — All account data saved to a file and reloaded automatically


Tech Stack


Language: C++ (C++11)
Concepts Used: Object-Oriented Programming (Classes, Encapsulation), File Handling (fstream), STL (vector, algorithm), Lambda Functions


How to Compile & Run

bashg++ -std=c++11 BankManagementApplication.cpp -o bank
./bank

On Windows:

bashbank.exe

File Structure

├── BankManagementApplication.cpp   # Main source code
├── accounts.dat                    # Auto-generated data file (created on first run)
└── README.md                       # Project documentation

Sample Menu

╔══════════════════════════════╗
║   BANK MANAGEMENT SYSTEM      ║
╠══════════════════════════════╣
║  1. Open New Account          ║
║  2. Login to Account          ║
║  0. Exit                      ║
╚══════════════════════════════╝

Expected Outcome

A secure and functional banking system capable of performing deposits, withdrawals, and balance inquiries while maintaining persistent customer records.

Author

Developed as part of the Thiranex Internship Program.
