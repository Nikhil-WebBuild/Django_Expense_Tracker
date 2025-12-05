# Expense Tracker

A simple expense tracker application built with Django and Django REST Framework.

## Features

- **User Authentication**: Register, Login, and Logout functionality.
- **Dashboard**: View your expenses in a list.
- **Add Expenses**: Track your spending by adding new expenses with categories.
- **API**: RESTful API (API to manage expenses)

## Technology Stack

- **Backend**: Django, Django REST Framework
- **Database**: SQLite
- **Frontend**: Django Templates

## How to setup

1. **Copy the project:**
   ```bash
   git clone <repository-url>
   cd expense_tracker
   ```

2. **Create and activate a virtual environment:**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the server:**
   ```bash
   python manage.py runserver
   ```

6. **Access the application:**
   Open your browser and go to `http://127.0.0.1:8000/`.