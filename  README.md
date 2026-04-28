# Personal Blog

A full-featured personal blog web application built with Django. Users can register, create posts, manage drafts, and organize content by categories.

## Features

- User registration and authentication
- Create, edit, delete blog posts
- Draft / Published post status
- Categories for posts
- Image upload for posts
- Personal dashboard for managing your posts
- Responsive design with Bootstrap 5

## Tech Stack

- Python 3
- Django
- Bootstrap 5
- SQLite
- Pillow

## Installation

1. Clone the repository
```bash
   git clone https://github.com/markiianpravetsst2024-cell/-personal-blog.git
   cd personal-blog
```

2. Create and activate virtual environment
```bash
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate     # Windows
```

3. Install dependencies
```bash
   pip install -r requirements.txt
```

4. Create `.env` file based on `.env.example`


5. Apply migrations
```bash
   python manage.py migrate
   python manage.py createsuperuser
   python manage.py runserver
```

## Environment Variables

| Variable | Description |
|----------|-------------|
| `SECRET_KEY` | Django secret key |
| `DEBUG` | Debug mode (True/False) |
| `ALLOWED_HOSTS` | Comma-separated list of allowed hosts |

## Author

Markiian — [GitHub](https://github.com/markiianpravetsst2024-cell)