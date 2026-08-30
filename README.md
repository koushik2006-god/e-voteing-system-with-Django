# E-Voting System with Django

A Django-based electronic voting system for managing elections, candidates, positions, and voter voting sessions.

## Overview

This project is designed to support a simple online voting workflow with:

- Admin management for election setup
- Candidate registration and position management
- Voter registration and validation
- Voting interface for selecting candidates
- Result tracking and vote summary
- Admin dashboard for election control

## Tech Stack

- Python
- Django
- SQLite database
- HTML/CSS/Bootstrap
- JavaScript

## Project Structure

- `account/` – user authentication and account logic
- `administrator/` – admin dashboard and management screens
- `voting/` – voting logic, models, and templates
- `e_voting/` – project configuration
- `media/` – uploaded candidate/media files
- `static/` – CSS, JS, and static assets

## Prerequisites

Make sure you have the following installed:

- Python 3.10+
- pip
- virtual environment support

## Installation

1. Clone the repository:

```bash
git clone https://github.com/koushik2006-god/e-voteing-system-with-Django.git
cd e-voteing-system-with-Django
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

On Linux/macOS:

```bash
source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing in your environment, install the main packages manually:

```bash
pip install django
```

4. Apply migrations:

```bash
python manage.py migrate
```

5. Create a superuser:

```bash
python manage.py createsuperuser
```

6. Run the development server:

```bash
python manage.py runserver
```

Then open:

```text
http://127.0.0.1:8000/
```

## Default Usage

- Log in as admin to manage election data
- Add positions, candidates, and voters
- Start voting workflow from the application
- View results from the admin panel

## Notes

- This project uses SQLite by default for local development.
- You may need to configure the project for production deployment before using it in a live environment.
- The database file and uploaded media are local runtime files and can be regenerated through migrations and admin actions.

## License

This project is available for educational and personal use. Add a license if you plan to publish or share it publicly.

## Contribution

Pull requests are welcome. If you want to improve the system, feel free to fork the repository and submit your changes.
