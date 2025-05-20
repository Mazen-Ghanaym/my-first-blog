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
  - Interactive UI with Bootstrap 5

## Technologies Used

- Python 3.12+
- Django 5.0+
- Bootstrap 5.1.3
- Font Awesome 6.0
- SQLite (Development)
- HTML5/CSS3
- JavaScript (ES6+)

## Getting Started

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/Blogs-Project.git
   cd Blogs-Project
   ```

1. Create a virtual environment

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

1. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

1. Configure environment

   ```bash
   cp .env.example .env
   # Edit .env file with your settings
   ```

1. Run migrations

   ```bash
   python manage.py migrate
   ```

1. Create a superuser (admin)

   ```bash
   python manage.py createsuperuser
   ```

1. Run the development server

   ```bash
   python manage.py runserver
   ```

Visit `http://127.0.0.1:8000` in your browser to see the application.

## Project Structure

```text
blog_project/
├── blog/                   # Main application
│   ├── templates/         # HTML templates
│   │   └── blog/         # Blog-specific templates
│   ├── static/           # Static files (CSS, JS)
│   ├── models.py         # Database models
│   ├── views.py          # View logic
│   ├── urls.py           # URL routing
│   ├── forms.py          # Form definitions
│   └── admin.py          # Admin interface config
├── blog_project/          # Project settings
│   ├── settings.py       # Project configuration
│   └── urls.py           # Main URL routing
├── requirements.txt       # Project dependencies
├── .env.example          # Example environment variables
├── .gitignore           # Git ignore rules
└── README.md            # Project documentation
```

## Features in Detail

### User Authentication

- Secure user registration with password validation
- Login with username/password
- Password reset functionality
- Protected routes for authenticated users

### Blog Management

- Create, edit, and delete blog posts
- Rich text editing for post content
- User-specific post management
- Responsive design for mobile devices

### Account Management

- Edit account details (username, email)
- Form validation and error handling
- Secure password management
- User-friendly interface

## Contributing

1. Fork the repository
1. Create your feature branch (`git checkout -b feature/YourFeature`)
1. Commit your changes (`git commit -m 'Add some feature'`)
1. Push to the branch (`git push origin feature/YourFeature`)
1. Open a Pull Request

## Acknowledgments

- Django documentation and community
- Bootstrap team for the excellent UI framework
- Font Awesome for the icons
