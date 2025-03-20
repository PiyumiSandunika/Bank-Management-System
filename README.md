# **🏦 Bank Management System**

A **C# Console Application** designed to manage bank accounts, transactions, loans and account searches efficiently. This system provides a user-friendly interface for performing various banking operations.

---

## **🌟 Features**

### **Account Management**
- **Create an Account**: Add new bank accounts with details like account number, name and balance.  
- **Update an Account**: Modify existing account details.  
- **Delete an Account**: Remove accounts from the system.  

### **Transaction Management**
- **Money Deposits**: Deposit money into an account.  
- **Money Withdrawal**: Withdraw money from an account.  
- **Money Transfer**: Transfer money between accounts.  
- **Transfer History**: View a history of all transactions in an account.  

### **Loan Management**
- **Apply for a Loan**: Request a loan with details like amount and interest rate.  
- **Loan Repayments**: Make repayments for existing loans.  
- **Calculate Interest**: Calculate interest for loans based on the principal amount and rate.  

### **Search & Sort Accounts**
- **Search by Account Number**: Find accounts using their unique account number.  
- **Search by Name**: Find accounts using the account holder's name.  
- **Sort by Balance**: Sort accounts based on their balance.  
- **Sort by Account Creation Date**: Sort accounts based on their creation date.  

---

## **🛠 Technologies Used**
- **Programming Language**: C#  
- **Framework**: .NET (Console Application)  
- **Data Storage**: CSV files (`bank_data.csv`)  

---

## **📦 Project Structure**
```
Bank-Management-System/
├── 📁 DSA Project/             # Main project folder
│   ├── 📁 bin/                 # Compiled binaries (auto-generated)
│   ├── 📁 obj/                 # Intermediate build files (auto-generated)
│   ├── 📄 Account.cs           # Class for managing account details
│   ├── 📄 AccountManagement.cs # Logic for account creation, update and deletion
│   ├── 📄 Bank.cs              # Main class for managing the bank system
│   ├── 📄 CsvDataHandler.cs    # Logic for reading/writing data to CSV files
│   ├── 📄 DSA Project.csproj   # Project configuration file
│   ├── 📄 DSA Project.sln      # Solution file for Visual Studio
│   ├── 📄 Loan.cs              # Class for managing loan details
│   ├── 📄 LoanManagement.cs    # Logic for loan applications, repayments and interest calculations
│   ├── 📄 Program.cs           # Main entry point of the application
│   ├── 📄 Save_Data.cs         # Logic for saving data to CSV files
│   ├── 📄 SearchAccount.cs     # Logic for searching and sorting accounts
│   ├── 📄 Transaction.cs       # Class for managing transaction details
│   ├── 📄 TransactionManagement.cs # Logic for deposits, withdrawals and transfers
├── 📄 bank_data.csv            # CSV file for storing account, transaction and loan data
├── 📄 README.md                # Project documentation
```

---

## **🔗 Clone the Repository**
```bash
git clone https://github.com/PiyumiSandunika/Bank-Management-System.git
```

---

## **🔧 Usage**
1. **Main Menu**:  
   - The application will display a menu with options for account management, transaction management, loan management and search/sort operations.  
2. **Follow Prompts**:  
   - Use the menu options to perform actions like creating accounts, depositing money, applying for loans or searching for accounts.  
3. **Exit**:  
   - Exit the application by selecting the appropriate option from the menu.  
