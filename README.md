# Django Blog Project

A feature-rich blog application built with Django, featuring user authentication, blog post management, and account customization.

## Features

- User Authentication (Register, Login, Logout)
- Account Management
  - Edit account details
  - Profile customization
- Blog Posts
  - Create, Read, Update, Delete (CRUD) operations
  - Rich text editing
  - User-specific post management

## Technologies Used

- Python 3.12
- Django
- Bootstrap 5
- Font Awesome
- SQLite (Development)

## Getting Started

1. Clone the repository
```bash
git clone <repository-url>
cd blog-project
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install django
```

4. Run migrations
```bash
python manage.py migrate
```

5. Create a superuser (admin)
```bash
python manage.py createsuperuser
```

6. Run the development server
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000` in your browser to see the application.

## Project Structure

```
blog_project/
├── blog/                   # Main application
│   ├── templates/         # HTML templates
│   ├── models.py         # Database models
│   ├── views.py          # View logic
│   └── urls.py           # URL routing
└── blog_project/          # Project settings
    ├── settings.py       # Project configuration
    └── urls.py           # Main URL routing
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
