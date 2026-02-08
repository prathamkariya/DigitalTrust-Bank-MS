
# DT Bank Management System

A robust, GUI-based Banking Management System built with **Python**, **Tkinter**, and **MySQL**. This application allows bank employees to manage customer accounts, perform financial transactions, and maintain secure records.

## 🚀 Features

* **Secure Employee Login:** Protected by `bcrypt` password hashing for secure authentication.
* **Customer Management:** Full CRUD (Create, Read, Update, Delete) functionality for customer profiles.
* **Transactions:** Real-time processing for deposits and withdrawals with balance verification.
* **Balance Inquiries:** Quick access to customer account standings.
* **Modern UI:** Clean and intuitive graphical interface designed with Tkinter.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **GUI Library:** Tkinter
* **Database:** MySQL
* **Security:** Bcrypt (Password Hashing)
* **Environment Management:** Dotenv (Credential protection)

## 📋 Prerequisites

Before running the application, ensure you have:
1.  **MySQL Server** installed and running.
2.  A database created (default name: `bank_management`).
3.  Python installed on your machine.

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/DT-Bank-Management.git](https://github.com/your-username/DT-Bank-Management.git)
   cd DT-Bank-Management
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```


3. **Configure Environment Variables:**
   * Copy the `.env.example` file and rename it to `.env`.
   * Open `.env` and enter your MySQL credentials:


```text
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=bank_management
EMP_USERNAME=emp_007

```


4. **Database Setup:**
Ensure your MySQL table `customers` has the following structure:
* `account_number`, `name`, `date_of_birth`, `phone_number`, `email`, `aadhar_number`, `address`, `account_type`, `balance`.


5. **Run the Application:**
```bash
python main.py

```



## 🔐 Security Note

This project uses `.env` files to keep sensitive database credentials out of version control. Ensure your `.env` file is listed in your `.gitignore` to prevent it from being pushed to GitHub.





## 📄 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

