# 🔐 LOGIN_REGISTER_PHP-ADMIN_USER

A simple **PHP & MySQL Authentication System** that provides user registration, login, logout, session management, and an Admin/User role system. This project is designed for beginners learning PHP and MySQL authentication.

## ✨ Features

* User Registration
* User Login & Logout
* Password Authentication
* Session Management
* Admin & User Roles
* Access Control
* Form Validation
* Responsive Interface
* MySQL Database Integration

---

## 🛠 Technologies Used

* PHP
* MySQL
* HTML5
* CSS3
* JavaScript
* XAMPP / Apache

---

## 📂 Project Structure

```text
LOGIN_REGISTER_PHP-ADMIN_USER/
│
├── admin/              # Admin dashboard
├── user/               # User dashboard
├── css/                # Stylesheets
├── images/             # Images
├── database/           # SQL database
├── login.php
├── register.php
├── logout.php
├── dashboard.php
├── config.php
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Zackik/LOGIN_REGISTER_PHP-ADMIN_USER.git
```

### 2. Move the project

For XAMPP:

```text
xampp/htdocs/
```

For Linux XAMPP:

```text
/opt/lampp/htdocs/
```

---

### 3. Create Database

Open **phpMyAdmin**

Create a database:

```sql
bank
```

Import the SQL file included in the project.

---

### 4. Configure Database

Open

```php
config.php
```

Update database credentials.

Example:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "bank";
```

---

### 5. Start Apache & MySQL

Run XAMPP and start

* Apache
* MySQL

---

### 6. Open Browser

```
http://localhost/LOGIN_REGISTER_PHP-ADMIN_USER/
```

---

## 👤 User Roles

### User

* Register account
* Login
* View personal dashboard
* Logout

### Admin

* Login
* Access Admin Dashboard
* Manage users
* View system information

---

## 📸 Screenshots

You can add screenshots here.

```
images/
├── login.png
├── register.png
├── dashboard.png
├── admin.png
```

Example:

```markdown
## Login

![Login](<img width="668" height="457" alt="Screenshot From 2026-07-18 02-45-56" src="https://github.com/user-attachments/assets/c1bea2e6-4759-42ad-90a2-1e950ffba96e" />
)

## Register

![Register](images/register.png)

## Dashboard

![Dashboard](images/dashboard.png)
```

---

## 🔒 Security

Current implementation includes:

* Password authentication
* Session-based login
* Role-based authorization
* Input validation

Recommended future improvements:

* Password hashing (`password_hash()`)
* Prepared Statements (PDO/MySQLi)
* CSRF Protection
* Remember Me
* Email Verification
* Forgot Password
* Login Rate Limiting

---

## 🚀 Future Improvements

* Profile Management
* Avatar Upload
* Email Verification
* Password Reset
* Two-Factor Authentication
* Activity Log
* Admin CRUD
* Responsive Dashboard
* Dark Mode

---

## 📖 Learning Objectives

This project helps beginners understand:

* PHP Authentication
* Sessions
* Cookies
* MySQL Database
* CRUD Operations
* Role-Based Access Control
* PHP Form Handling

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is intended for educational purposes.

---

## 👨‍💻 Author

**Thanh Bui**

GitHub: https://github.com/Zackik

---

⭐ If you find this project helpful, please consider giving it a **Star** on GitHub.
