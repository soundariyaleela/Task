# Codealpha_Tasks

🔗 URL Shortener – Flask Web Application
--------------------------------

A simple and efficient URL Shortener web application built using Flask and SQLite, deployed on Render. This application allows users to convert long URLs into short, shareable links and automatically redirects users to the original URL when accessed.

🚀 Live Demo
-----
👉 Deployed URL:
https://codealpha-tasks-6jda.onrender.com 

🛠️ Technologies Used
---------------------
Python

Flask

SQLite

HTML / CSS

Gunicorn

Render (Cloud Deployment)

✨ Features
-------------------
Shortens long URLs into compact links

Validates URLs before shortening

Redirects short URLs to the original website

Stores URLs with timestamps

Uses SQLite database

Deployed and accessible online

📁 Project Structure
----------------
URL-Shortener/

├── app.py               # Main Flask application

├── urls.db              # SQLite database

├── requirements.txt     # Project dependencies

├── templates/
│   └── index.html       # Frontend HTML

├── static/
│   └── style.css        # (Optional) Styling

├── README.md            # Project documentation


⚙️ Installation & Local Setup
-------------
1️⃣ Clone the repository
git clone https://github.com/soundariyaleela/Codealpha_Tasks.git
cd Codealpha_Tasks

2️⃣ Create and activate virtual environment
python -m venv venv
venv\Scripts\activate   # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the application
python app.py


Open browser and visit:

http://127.0.0.1:5000
-----------------

🌐 Deployment (Render)
------------
Runtime: Python

Start Command:

gunicorn app:app

Database initializes automatically on first run


👩‍💻 Author
-------
Soundariya Leela M

📜 License
-----
This project is for educational purposes.

