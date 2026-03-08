# Weather Django Python App

A Django-based weather application that provides real-time weather information for cities worldwide. This app demonstrates integration with external weather APIs and follows Django best practices.

## Features

- 🌤️ **Real-time Weather Data**: Get current weather conditions for any city
- 🔍 **City Search**: Search functionality to find weather for specific locations
- 📊 **Weather Details**: Temperature, humidity, wind speed, and atmospheric conditions
- 🎨 **Clean UI**: User-friendly interface with responsive design
- 📱 **Mobile Friendly**: Works on desktop and mobile devices

## Tech Stack

- **Backend**: Django 4.x (Python 3.x)
- **Frontend**: HTML5, CSS3, Bootstrap
- **API**: OpenWeatherMap API (or similar weather service)
- **Database**: SQLite3 (development) / PostgreSQL (production ready)
- **Version Control**: Git

## Project Structure

Weather_Django_Python_App/
├── manage.py # Django management script
├── weather_app/ # Main application folder
│ ├── migrations/ # Database migrations
│ ├── templates/ # HTML templates
│ ├── static/ # CSS, JS, images
│ ├── models.py # Database models
│ ├── views.py # View logic
│ ├── urls.py # App-specific URLs
│ ├── forms.py # Form handling
│ └── admin.py # Admin interface config
├── weather_project/ # Project configuration folder
│ ├── settings.py # Django settings
│ ├── urls.py # Main URL configuration
│ └── wsgi.py # WSGI config for deployment
└── requirements.txt # Python dependencies


### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Git

### Step-by-Step Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/uraz-baltabayev/Weather_Django_Python_App.git
   cd Weather_Django_Python_App
Create and activate virtual environment

bash
# On macOS/Linux
python3 -m venv venv
source venv/bin/activate

# On Windows
python -m venv venv
venv\Scripts\activate
Install dependencies

bash
pip install -r requirements.txt
Set up environment variables
Create a .env file in the root directory:

env
SECRET_KEY=your_django_secret_key
WEATHER_API_KEY=your_weather_api_key
DEBUG=True
Run database migrations

bash
python manage.py migrate
Create a superuser (optional)

bash
python manage.py createsuperuser
Run the development server

bash
python manage.py runserver

## Access the application
Open your browser and navigate to http://127.0.0.1:8000