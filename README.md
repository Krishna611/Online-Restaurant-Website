# 🍽️ Online Restaurant Website

An online food ordering system built using **Flask (Python)**, **SQLite**, **HTML/CSS/JS**.  
It allows users to browse menus, add items to a cart, and checkout.

---

## 🚀 Features
- 🔑 User login system
- 📂 Menu browsing by category
- 🛒 Add to cart & checkout
- 💳 Order confirmation page
- 🔍 Search functionality
- 🎨 Responsive UI with CSS & JavaScript
- 🗄️ SQLite database for storing user & order data

---

## 📂 Project Structure
Online-Restaurant-main/
│── app.py # Main Flask app
│── init_db.py # Database initialization
│── database.db # SQLite database
│── requirements.txt # Dependencies
│── Procfile # For deployment (Heroku)
│
├── templates/ # HTML pages
│ ├── index.html
│ ├── login.html
│ ├── cart.html
│ ├── category.html
│ ├── checkout.html
│ ├── order_confirmation.html
│ └── search_results.html
│
├── static/ # CSS & JavaScript
│ ├── style.css
│ └── script.js
│
└── venv/ # Virtual environment (ignore in GitHub)

yaml
Copy
Edit

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/online-restaurant.git
cd online-restaurant
2️⃣ Create Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Initialize Database
bash
Copy
Edit
python init_db.py
5️⃣ Run the Application
bash
Copy
Edit
python app.py
App will run on 👉 http://127.0.0.1:5000/

🛠️ Technologies Used
Backend: Flask (Python)

Database: SQLite

Frontend: HTML, CSS, JavaScript

Deployment: Heroku (via Procfile)




🔐 Login Credentials
You can log in using the following test account:

Username: krishna

Password: krishna123
