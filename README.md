# My Library – Flask Web App

A simple Flask web application to manage a personal book library.

# Features
- Add new books
- View all books
- Edit book ratings
- Delete books
- Persistent storage using SQLite
- Built with Flask & SQLAlchemy

# Tech Stack
- Python
- Flask
- Flask-SQLAlchemy
- SQLite
- HTML (Jinja2 templates)

# Project Structure
My-Library/
├── main.py
├── templates/
│   ├── index.html
│   ├── add.html
│   └── edit.html
├── requirements.txt
└── README.md

# How to Run Locally

```bash
git clone https://github.com/sarthaksatapathy/my-library.git
cd my-library
pip install -r requirements.txt
python main.py
Then run:
http://127.0.0.1:5000
