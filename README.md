# StockPilot – Inventory Management System

A Django-based inventory management system to manage products, stock levels and low-stock alerts.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)

## Features

- Product registration, editing, search and deletion
- Stock-in and stock-out tracking
- Stock-level management
- Low-stock alerts

## Tech Stack

- **Backend:** Python, Django
- **Database:** SQL (SQLite)
- **Frontend:** HTML, Bootstrap

## Getting Started

1. Clone the repository

```bash
git clone https://github.com/Yaswanthnaikk/StockPilot-Inventory-Management.git
cd StockPilot-Inventory-Management
```

2. Create and activate a virtual environment

```bash
python -m venv venv
venv\Scripts\activate        # Windows
source venv/bin/activate      # macOS / Linux
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Apply migrations and create an admin user

```bash
python manage.py migrate
python manage.py createsuperuser
```

5. Run the server

```bash
python manage.py runserver
```

Open http://127.0.0.1:8000/ in your browser.

<!-- Add screenshots here: create a "screenshots" folder in the repo, upload images, then use ![Home page](screenshots/home.png) -->

## What I Learned

- Designing Django models and database relationships
- Building CRUD operations with the Django ORM
- Handling stock logic and alert conditions

## Author

**Yaswanth Naik Desavath**
[GitHub](https://github.com/Yaswanthnaikk) | [LinkedIn](https://linkedin.com/in/yaswanth-naik) | dyaswanthnaiknaik@gmail.com
