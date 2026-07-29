# 🏦 Basic Banking Operations

**A console-based bank management system built in C++.** Handles customer account management and core banking transactions, with file-based persistence and user access control.

---

## ✨ Features

- 👤 **Customer Account Management** — Add, delete, update, and search client records
- 💰 **Account Transactions** — Deposit, withdraw, and view balance
- 🔐 **User Management & Access Control** — Authenticated users with permission-based operations
- 💾 **File-Based Data Persistence** — Client and user data stored and retrieved from text files (`Clients.txt`, `Users.txt`)

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| **Language** | C++ |
| **Data Storage** | File I/O (`.txt`) |
| **Interface** | Console (CLI) |

---

## 📂 Data Storage

The system uses simple, file-based persistence instead of a database engine:

- **`Clients.txt`** — Stores customer account records (account number, name, balance, etc.)
- **`Users.txt`** — Stores system users and their access permissions

This approach keeps the project lightweight and dependency-free, making it easy to run and inspect without any external database setup.

---

## 🔐 User Roles & Permissions

Access to the system is gated through user authentication. Each user is granted specific permissions (e.g., view balances, perform transactions, manage clients), and the system checks these permissions before allowing an operation to proceed.

---

## 🚀 Getting Started

### Prerequisites
- A C++ compiler (e.g., g++, MSVC, or any standard C++ IDE)

### Installation

```bash
# Clone the repository
git clone https://github.com/Muhammed-Ali-Asfur/BankaSystem.git

# Navigate to the project directory
cd BasicBankingOperations

# Compile the project
g++ main.cpp -o BankingSystem

# Run the application
./BankingSystem
```

> 💡 Ensure `Clients.txt` and `Users.txt` exist in the working directory before running — the application reads from and writes to these files.

---

## 📬 Contact

Feel free to reach out or open an issue if you have questions or suggestions.

---

⭐ If you found this project useful, consider giving it a star!
