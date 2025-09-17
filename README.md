# Spam Message Detection with Python and Django

A web application that detects whether a message is **spam** or **not spam** using Machine Learning, built with **Python**, **Django**, and **HTML/CSS**.

## 🚀 Project Overview

This project is designed to help detect spam messages automatically. It uses a trained Machine Learning model to classify messages entered by users via a web interface as either **Spam** or **Ham (Not Spam)**.

### Key Features
- User-friendly web interface built using Django.
- Spam detection powered by a Python Machine Learning model.
- Easy message input and classification result display.
- Simple and responsive front-end design.

## 📚 Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML, CSS
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Database**: SQLite (default Django database)

## ⚙️ Installation Instructions

### 1️⃣ Clone the repository
```bash
https://github.com/neelisaimahesh/Spam-message-detection.git
cd spam-message-detection-with-python-and-django
2️⃣ Create and activate a virtual environment
bash
Copy code
python -m venv env
source env/bin/activate  # For Linux/Mac
# OR
env\Scripts\activate  # For Windows
3️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Apply Migrations
bash
Copy code
python manage.py migrate
5️⃣ Run the development server
bash
Copy code
python manage.py runserver
👉 Open your browser and navigate to: http://127.0.0.1:5500/Only%20Web%20Interface/index.html

