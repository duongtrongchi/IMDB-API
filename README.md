# IMDb API Clone
This Django project aims to replicate the functionality of the IMDb API using Django REST Framework. With this project, you'll be able to retrieve information about movies, TV shows, actors, directors, and more, just like you would with the official IMDb API.

## Getting Started
Follow these instructions to set up the project on your local machine:

### Prerequisites
Make sure you have the following installed on your system:

- Python [version]
- Django [version]
- Django REST Framework [version]

### Installation
Clone the repository: ```git clone https://github.com/duongtrongchi/IMDB-API.git```
Navigate to the project directory: IMDB-API
Install dependencies: ```pip install -r requirements.txt```
Apply migrations: ```python manage.py migrate```
Start the development server: ```python manage.py runserver```

## Project Structure
Here's an overview of the project's structure:

- api/: Contains the Django app for the API.
- project_name/: Contains the project settings and configuration.
- templates/: If any HTML templates are needed for documentation or administration.
- static/: Static files such as CSS, JavaScript, and images.
- requirements.txt: Lists all Python dependencies for the project.


## API Endpoints
The API provides endpoints for various IMDb-like functionalities, including:

- Retrieving information about movies and TV shows.
- Searching for movies, TV shows, actors, directors, etc.
- Adding new movies or TV shows to the database.

Refer to the API documentation for details on available endpoints and usage.