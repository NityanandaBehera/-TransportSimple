#Transport Simple Assessment

A Django project for TransportSimple.

## Prerequisites

- Python 3.8+
- pip
- Git

## Getting Started

1. Clone the repository:
```bash
https://github.com/NityanandaBehera/-TransportSimple.git
cd TransportSimple
```

2. Create and activate virtual environment:
```bash
# Create virtual environment
python -m venv env

# Activate virtual environment
# On Windows:
env\Scripts\activate
# On macOS/Linux:
source env/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up the database:
```bash
# Create database migrations
python manage.py makemigrations

# Apply migrations
python manage.py migrate
```

5. Create superuser (optional):
```bash
python manage.py createsuperuser
```

6. Start the development server:
```bash
python manage.py runserver
```
