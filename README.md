# 📚 StudyBud Setup Guide 🌟

Welcome to StudyBud! This guide will walk you through the setup process to get StudyBud up and running on your local machine.

## Getting Started 🚀

1. **Clone the repository:**
   ```bash
   git clone <repo-url>

2. **Navigate to the project directory:**
    ```bash
    cd studybud
    
3. **Create a virtual environment:**
    ```bash
    python -m venv env

4. **Activate the virtual environment:**
    
    For Windows:
    ```bash
    env\Scripts\activate
    ```
    
    For Unix or MacOS:
    ```bash
    source env/bin/activate
    
5. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    
6. **Apply database migrations:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    
7. **Run the development server:**
    ```bash
    python manage.py runserver
    
8. **Access StudyBud in your browser:**

    Open http://localhost:8000 in your web browser.
