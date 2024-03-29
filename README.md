# Stock-Prediction

This is a web application built with Django for predicting stock prices.

## Project Structure

- `app/`: This is the main application directory. It contains the following important files:

  - `models.py`: Defines the data models used in the application.
  - `views.py`: Handles the application's routing and views.
  - `admin.py`: Contains settings for the Django admin interface.
  - `tests.py`: Contains tests for the application.
  - `Data/`: Contains data files used by the application.
  - `templates/`: Contains HTML templates for the application's views.
  - `static/`: Contains static files like CSS, JavaScript, and images.

- `core/`: This directory contains the core settings for the Django project, including `settings.py`, `urls.py`, and `wsgi.py`.

- `manage.py`: This is a command-line utility that lets you interact with the Django project in various ways.

- `virtualenv/`: Contains the Python virtual environment for the project.

## Setup

To set up the project, first create a Python virtual environment and activate it. Then, install the required packages:

```sh
python -m venv virtualenv
source virtualenv/bin/activate
pip install -r requirements.txt

Next, apply the migrations to set up your database schema:
python manage.py migrate

Finally, start the Django development server:
python manage.py runserver

Now you can access the application at http://localhost:8000.

## Testing
To run the tests for the application, use the following command:
python manage.py test
```
