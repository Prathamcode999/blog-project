# Django Blog Project

This repository contains a fully functional blog application built with Django, designed to provide an intuitive and user-friendly blogging experience. 

## Features

- **Blog Creation and Management**: Create, edit, and manage blog posts with ease.
- **User Dashboards**: Personalized dashboards for users to manage their content and activities.
- **Media Handling**: Upload and manage media files seamlessly.
- **Responsive Templates**: Pre-designed templates to ensure a modern and responsive interface.
- **Database Integration**: Comes with SQLite as the default database for easy setup.
- **Modular Design**: Organized into separate apps for blogs, dashboards, and assignments for better maintainability.

## Setup Instructions

1. Clone the repository:
   ```bash
   https://github.com/Prathamcode999/blog-project.git
2. Navigate to the project directory:
   ```bash
   cd django-blog-project
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
4. Run migrations:
   ```bash
   python manage.py migrate
5. Start the development server:
   ```bash
   python manage.py runserver
6. Access the application at http://127.0.0.1:8000/.


##File Structure

- assignments/: Handles assignment-related functionalities.
- blog_main/: Core configurations for the Django project.
- blogs/: Manages blog-related features and models.
- dashboards/: Provides user dashboard functionalities.
- templates/: HTML templates for the application.
- media/: Directory for uploaded media files.
- db.sqlite3: SQLite database for local developement


   
