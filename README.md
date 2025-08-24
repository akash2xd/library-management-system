# 📚 Library Management System (C Project)

[![Language](https://img.shields.io/badge/Language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A **console-based Library Management System** written in C.  
It provides a simple and secure way to manage books in a library — including adding, deleting, editing, searching, and viewing records — with an **admin authentication system**.

---

## 🚀 Features

- 🔑 **Admin Authentication**  
  Secure login/signup with password masking (`*`) and ability to change password anytime.  

- 📘 **Book Management**  
  Add, edit, and delete books with details such as Category, ID, Name, Author, Quantity, Price, and Rack Number.  

- 🔍 **Search Functionality**  
  Find books quickly by **Book ID** or **Book Name**.  

- 📂 **Persistent Data Storage**  
  Records stored in `Record.dat` for long-term usage.  

- 🖥️ **User-Friendly Console UI**  
  Neat, structured menus and navigation using `gotoxy()` for positioning.  

---

📦 Library-Management-System
├── 📄 Library_Management.c # Main program
├── 📄 core_functions.h # Book operations (Add, Search, Check ID, etc.)
├── 📄 general_functions.h # Utilities (Password, gotoxy, etc.)
├── 📄 variables.h # Structs, globals, and prototypes
├── 🔑 password.dat # Stores admin password (auto-generated)
├── 📑 Record.dat # Stores book records (auto-generated)
└── ⚙️ Library_Management.exe # Windows executable


---

## ⚙️ Requirements

- **Compiler:** GCC / MinGW / Turbo C  
- **OS:** Windows (due to `conio.h` and `windows.h` usage)  
- **Dependencies:**  
  - `stdio.h`  
  - `stdlib.h`  
  - `string.h`  
  - `time.h`  
  - `conio.h`  
  - `windows.h`  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system

## 📂 Project Structure

---

## ⚙️ Requirements

- **Compiler:** GCC / MinGW / Turbo C  
- **OS:** Windows (due to `conio.h` and `windows.h` usage)  
- **Dependencies:**  
  - `stdio.h`  
  - `stdlib.h`  
  - `string.h`  
  - `time.h`  
  - `conio.h`  
  - `windows.h`  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
Compile:

gcc Library_Management.c -o Library_Management.exe


Run:

./Library_Management.exe


📌 First Run: You’ll be asked to set up an Admin Password.
🖼️ Main Menu Preview
1. Add Books
2. Delete Book
3. Search Book
4. View Book List
5. Edit Book Record
6. Change Password
7. Close Application

🔒 Security Notes

Password input is hidden with * characters.

Password is stored securely in password.dat (binary file).

Keep password.dat private to maintain security.

✨ Future Enhancements

📖 Add issuing & returning of books with due dates.

👥 Track student/user records linked with issued books.

📊 Export book records into .csv or .txt.

💻 Add Linux support by replacing conio.h and windows.h.

👨‍💻 Author

Aragha Gupta
📧 Email: (exlucario2op@gmail.com)
🏫 Meghnad Saha Institute of Technology

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.


---

✅ This is the **complete, polished README.md file** — looks good on GitHub out of the box.  

Do you want me to also prepare the **MIT `LICENSE` file text** so your repo is fully ready for publishing?
