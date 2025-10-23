# 🔐 Flask Authentication System

A simple and secure **user authentication system** built using **Flask**, **Flask-Bcrypt**, and **SQLite**.  
This app allows users to **register, login, and logout** with securely hashed passwords using bcrypt.  
The focus is on implementing **basic authentication flow** and **secure password handling**.

---



## ⚙️ Features

✅ User Registration  
✅ Secure Password Hashing with `bcrypt`  
✅ User Login with Token/Session Handling  
✅ Logout Functionality  
✅ Flash Messages for Feedback  
✅ Simple HTML Frontend for Login & Register Pages  

---

## 🧰 Tech Stack

- **Backend:** Flask (Python)
- **Database:** SQLite
- **Security:** Flask-Bcrypt (for password hashing)
- **Frontend:** HTML + CSS (in Flask templates)

---

## 🧩 Installation Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/rishee10/Authentication-System.git
cd Authentication-System
```

### 2️⃣ Create Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate       # for Mac/Linux
venv\Scripts\activate          # for Windows
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```
python app.py
```

### 5️⃣ Access in Browser

Open your browser and visit:

```
http://127.0.0.1:5000/
```
