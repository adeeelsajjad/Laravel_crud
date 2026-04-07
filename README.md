##🎓 Student Data CRUD Application
A simple yet powerful Student Management System built with Laravel that demonstrates full CRUD (Create, Read, Update, Delete) functionality. This project is designed for learning and practicing Laravel fundamentals with a clean UI.

📖 Table of Contents
✨ Features
🛠 Tech Stack
📂 Project Structure
⚙️ Installation
🚀 Usage
📸 Screenshots
🎯 Learning Outcomes
🤝 Contributing
📄 License
👨‍💻 Author
✨ Features

✔️ Create new student records
✔️ Display all students in a structured table
✔️ Update/edit student information
✔️ Delete student records
✔️ Form validation for data accuracy
✔️ Clean and responsive UI

🛠 Tech Stack
Technology	Description
Laravel	PHP framework for backend
PHP	Server-side scripting
MySQL	Database management
HTML5	Structure of web pages
CSS3 / Bootstrap	Styling and responsiveness
📂 Project Structure
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
⚙️ Installation

Follow these steps to set up the project locally:

🔹 1. Clone Repository
git clone https://github.com/huzaifakhalid07/Laravel_crud.git
cd Laravel_crud
🔹 2. Install Dependencies
composer install
🔹 3. Setup Environment File
cp .env.example .env

Update database credentials:

DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=
🔹 4. Generate Application Key
php artisan key:generate
🔹 5. Run Database Migrations
php artisan migrate
🔹 6. Start Development Server
php artisan serve

👉 Open in browser:

http://127.0.0.1:8000
🚀 Usage
Open the application in your browser
Add a new student using the form
View all students in the list
Edit/update student details
Delete records when needed
📸 Screenshots

(Add your screenshots here for better presentation)

Example:

/screenshots/home.png
/screenshots/add-student.png
🎯 Learning Outcomes

This project helps you understand:

Laravel MVC architecture
Routing and controllers
Database migrations
CRUD operations in real applications
Form handling & validation
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a new branch
Make your changes
Submit a pull request
📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Huzaifa Khalid

GitHub: https://github.com/huzaifakhalid07
Project Repo: https://github.com/huzaifakhalid07/Laravel_crud
⭐ Support

If you like this project, please ⭐ star the repository and share it!
