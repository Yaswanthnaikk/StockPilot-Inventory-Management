# StockPilot — Inventory and Stock Management System

A Django portfolio project for managing a small product inventory.

## Features
- User registration, login, and logout
- Add, view, edit, and delete products
- SKU, category, quantity, unit price, and reorder level
- Stock-in and stock-out operations
- Stock movement history
- Low-stock alerts
- Product search
- Authenticated REST API with per-user data isolation
- Django admin and automated tests

## Windows / VS Code setup
Open the extracted `stockpilot_inventory_fixed` folder in VS Code. Open Terminal → New Terminal and run each command separately:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python manage.py makemigrations inventory
python manage.py migrate
python manage.py runserver
```

Open http://127.0.0.1:8000/ and register an account.

If PowerShell blocks activation, use Command Prompt in VS Code and run:
```cmd
.venv\Scripts\activate.bat
```

## Useful URLs
- `/` — inventory dashboard
- `/accounts/register/` — register
- `/accounts/login/` — login
- `/admin/` — Django admin
- `/api/products/` — authenticated REST API

## Tests
```powershell
python manage.py test
```

## Important
This is a learning project, not production inventory software. Before real business use, add proper deployment secrets, HTTPS, database backups, stronger role permissions, audit controls, and concurrency testing. Do not use real business records until it has been reviewed and secured.
