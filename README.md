# Spare Parts Management System

A web-based Spare Parts Management System built with **Django** and **SQLite**. This application allows users to manage categories, products, purchases,Paymen and sales of auto spare parts efficiently through a clean admin interface.

## 🚀 Features

- Admin authentication and dashboard
- Category and subcategory management
- Add, update, delete spare parts/products
- Purchase & sales tracking
- Invoice and stock management
- Simple, modular Django project structure

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Database**: SQLite (default Django DB)
- **Frontend**: HTML, CSS, Bootstrap
- **Others**: Django Admin

## 📦 Installation & Setup

### Prerequisites

- Python 3.x installed
- pip package manager
- Virtualenv (optional but recommended)

### Setup Steps

1. **Clone the Repository**
   git clone https://github.com/PavanKHegde/Spare-Parts-Management-System.git
   cd Spare-Parts-Management-System

2. **Create and Activate a Virtual Environment (optional)**
    python -m venv env
    source env/bin/activate        # On Linux/Mac
    env\Scripts\activate           # On Windows
    

3.**Install Dependencies**
    pip install -r requirements.txt

4. **Apply Migrations**

  python manage.py migrate
  
5. **Create Superuser**
  python manage.py createsuperuser

6. **Run the Server**

7.**python manage.py runserver**
  Access the App

   Open your browser and go to:
  http://localhost:8000/
