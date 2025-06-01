🏦 Project Title: Secure Banking Application in Python

🧾 Problem Statement:

In today’s digital world, users expect secure and simple banking systems that protect their personal data and enable basic transactions with ease. However, many beginner banking applications lack essential security features like password strength checks and two-factor authentication (2FA).

The goal of this project is to design and implement a secure, console-based banking system in Python that allows users to:

- Register with validated personal details such as Aadhaar and mobile number  
- Use strong password policies for enhanced security  
- Authenticate with OTP-based two-factor login  
- Perform essential banking functions: checking balance, depositing, withdrawing money, and viewing transaction history

This project addresses the problem of building a lightweight yet secure banking system for educational use, focusing on data validation, user authentication, and safe transaction handling without using databases or external storage.


📌 Project Description:
This project is a console-based Secure Banking Application built in Python. It simulates a simple banking system that emphasizes user authentication, data validation, and basic account operations.

✅ Key Features:

User Registration
- Collects username, strong password, Aadhaar number (16-digit), and mobile number (10-digit).
- Performs input validation to ensure correctness and prevent weak entries.

Password Strength Checker
- Ensures the password meets all security requirements:
  - At least 8 characters
  - Includes lowercase, uppercase, digits, and special characters

User Login with 2FA (Two-Factor Authentication)
- Validates password and mobile number
- Generates and verifies a 6-digit OTP to simulate secure login

Account Operations (Post-login)
- Check Balance
- Deposit Money
- Withdraw Money (with insufficient balance check)
- Transaction History tracking for deposits and withdrawals

Data Storage Using Dictionary
- All user details and transactions are stored in a dictionary structure:

users = {
    "username": {
        "password": "...",
        "aadhaar": "...",
        "mobile": "...",
        "balance": 0.0,
        "transactions": [...]
    }
}

🧠 Learning Objectives:
Practice working with:
- Dictionaries and lists
- Input validation and loops
- Random number generation (OTP simulation)
- String handling and condition checks
- Implement basic security principles (password strength & OTP)

🚀 How to Run:
- Run the Python script.
- Register as a new user.
- Login using the registered credentials and mobile OTP.
- Perform banking actions like deposit, withdraw, and view transaction history.
"""

file_path = "/mnt/data/secure_banking_project_description.txt"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(project_description)

file_path
