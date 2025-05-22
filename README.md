# 📚 Online Library Management System (OLMS)

A full-stack web application for managing library operations, built using **Python 3.13**, **Django**, and **MySQL**, with a responsive frontend designed in **HTML, CSS, Bootstrap**, and **JavaScript**.

---

## 🚀 Features

- 🔐 Role-based login system (Admin & Student)
- 📕 Book management (Add, View, Edit, Delete)
- 🎓 Student registration and account management
- 📗 Book issue/return tracking
- 🧾 Fine management (manual)
- 📊 Admin dashboard for tracking all operations
- 🌐 Web-based access from any browser

---

## 🛠️ Tech Stack

| Layer      | Technology                |
|------------|---------------------------|
| Frontend   | HTML, CSS, Bootstrap, JS  |
| Backend    | Python 3.13, Django       |
| Database   | MySQL                     |
| IDE Used   | PyCharm                   |
| Server     | Django development server |

---

## ⚙️ Setup Instructions

1. **Clone this repo**
   ```bash
   git clone https://github.com/R3DuX-7/OLMS.git

2. Create & activate a virtual environment

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

Install requirements
pip install -r requirements.txt

4.Set up the MySQL database
Create a new database (e.g., olms_db)
Configure your database credentials in settings.py

5.Run migrations
python manage.py makemigrations
python manage.py migrate

6.Start the server
python manage.py runserver

7.Login
Visit http://127.0.0.1:8000
Use the Django admin panel to create users or use the registration module

📌 Future Enhancements
📲 Mobile responsive design
🧠 Book recommendation engine using AI
📤 Email/SMS notifications
🧾 Automated fine calculations
🔒 CAPTCHA & Forgot password
📶 Cloud deployment

 Developed By
Akshat Gangrade
📧 akshat2215@gmail.com
🎓 Roll No: 22COA2BCA0087

Jeet Singh Bais
📧 jeetsinghbais7@gmail.com
🎓 Roll No: 22COA2BCA0039

Project Report Link - https://drive.google.com/file/d/1kF6Ufr-i2rg7Jx7GwbpHGrxM7Ajcynfw/view?usp=sharing 
Project PPT Link- https://docs.google.com/presentation/d/1YkMCvzjKWqSHT0tjU8-F8AsC_C2WuyVF/edit?usp=sharing&ouid=105084111787398362081&rtpof=true&sd=true

📜 License
This project is for educational purposes only. No commercial use permitted without permission.
