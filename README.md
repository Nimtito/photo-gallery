#  Photo Gallery

## Description

Photo Gallery is a Django web application that allows users to register, log in, browse photos, view photo details, filter photos by tags, like or dislike photos, and manage their profiles. The application uses PostgreSQL for data storage and Tailwind CSS for a responsive user interface.
## Features

- User Registration & Login
- User Profile Management
- Browse Photo Gallery
- View Photo Details
- Filter Photos by Tags
- Like and Dislike Photos
- Responsive Design
## Technologies Used

- Python 3
- Django 3
- PostgreSQL
- HTML5
- CSS3
- Tailwind CSS
- Git

## Installation

1. Create and activate a virtual environment

```bash
python -m venv myenv
myenv\Scripts\activate
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Configure PostgreSQL in `settings.py`.

4. Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

5. Create a superuser

```bash
python manage.py createsuperuser
```

6. Run the server

```bash
python manage.py runserver
```
## Author

**Nimrod Kyalo**