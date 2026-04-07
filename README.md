
---

# 🎓 Student Data CRUD Application

![Laravel](https://img.shields.io/badge/Laravel-Framework-red?logo=laravel)
![PHP](https://img.shields.io/badge/PHP-Backend-blue?logo=php)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)
![License](https://img.shields.io/badge/License-MIT-green)

A simple yet powerful **Student Management System** built with **Laravel** that demonstrates full **CRUD (Create, Read, Update, Delete)** functionality. This project is designed for learning and practicing Laravel fundamentals with a clean UI.

---

## 📖 Table of Contents

* [✨ Features](#-features)
* [🛠 Tech Stack](#-tech-stack)
* [📂 Project Structure](#-project-structure)
* [⚙️ Installation](#️-installation)
* [🚀 Usage](#-usage)
* [📸 Screenshots](#-screenshots)
* [🎯 Learning Outcomes](#-learning-outcomes)
* [🤝 Contributing](#-contributing)
* [📄 License](#-license)
* [👨‍💻 Author](#-author)

---

## ✨ Features

✔️ Create new student records
✔️ Display all students in a structured table
✔️ Update/edit student information
✔️ Delete student records
✔️ Form validation for data accuracy
✔️ Clean and responsive UI

---

## 🛠 Tech Stack

| Technology           | Description                |
| -------------------- | -------------------------- |
| **Laravel**          | PHP framework for backend  |
| **PHP**              | Server-side scripting      |
| **MySQL**            | Database management        |
| **HTML5**            | Structure of web pages     |
| **CSS3 / Bootstrap** | Styling and responsiveness |

---

## 📂 Project Structure

```
Laravel_crud/
│
├── app/                # Application logic (Controllers, Models)
├── database/           # Migrations & seeders
├── public/             # Public assets
├── resources/views/    # Blade templates (UI)
├── routes/             # Web routes
├── .env                # Environment configuration
├── composer.json       # Dependencies
└── artisan             # Laravel CLI
```

---

## ⚙️ Installation

Follow these steps to set up the project locally:

### 🔹 1. Clone Repository

```bash
git clone https://github.com/huzaifakhalid07/Laravel_crud.git
cd Laravel_crud
```

### 🔹 2. Install Dependencies

```bash
composer install
```

### 🔹 3. Setup Environment File

```bash
cp .env.example .env
```

Update database credentials:

```
DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=
```

### 🔹 4. Generate Application Key

```bash
php artisan key:generate
```

### 🔹 5. Run Database Migrations

```bash
php artisan migrate
```

### 🔹 6. Start Development Server

```bash
php artisan serve
```

👉 Open in browser:

```
http://127.0.0.1:8000
```

---

## 🚀 Usage

1. Open the application in your browser
2. Add a new student using the form
3. View all students in the list
4. Edit/update student details
5. Delete records when needed

---

## 📸 Screenshots

> *(Add your screenshots here for better presentation)*

Example:

```
/screenshots/home.png
/screenshots/add-student.png
```

---

## 🎯 Learning Outcomes

This project helps you understand:

* Laravel MVC architecture
* Routing and controllers
* Database migrations
* CRUD operations in real applications
* Form handling & validation

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Adeel Sajjad**

* GitHub: [https://github.com/adeeelsajjad](https://github.com/adeeelsajjad)
* Project Repo: [https://github.com/adeeelsajjad/Laravel_crud](https://github.com/adeeelsajjad/Laravel_crud)

---

## ⭐ Support

If you like this project, please ⭐ star the repository and share it!

---

