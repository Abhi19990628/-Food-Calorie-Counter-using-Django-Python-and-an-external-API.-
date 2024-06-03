# Nutrition and Blog Application

This project is a Django-based web application that provides users with nutrition information based on their queries and displays blog posts fetched from an external API. The application includes user authentication, a contact form, and basic CRUD functionality

## Features

- **Home Page**: Users can enter a query to get nutrition information using the API Ninjas Nutrition API.
- **Blog Page**: Displays blog posts fetched from the JSONPlaceholder API.
- **Contact Page**: Users can submit their contact information and messages.
- **User Registration**: Users can create an account.
- **User Login/Logout**: Users can log in and log out.

## Setup and Installation

### Prerequisites

- Python 3.x
- Django 3.x or later
- Requests library

### Installation on Windows

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Abhi19990628/-Food-Calorie-Counter-using-Django-Python-and-an-external-API.-
    ```

2. **Create and activate a virtual environment:**
    ```bash
    pip install virtualenv
    virtualenv name your env (my_env) 
    cd\my_env\scripts\ ./actiavte
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run migrations:**
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser:**
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

7. Open your browser and go to `http://127.0.0.1:8000`.

## Configuration

- **API Keys**: Update the `home` view to use your own API key for the API Ninjas Nutrition API.

## Project Structure
health-app/
├── health_guide/
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── templates/
│ ├── home.html
│ ├── blog.html
│ ├── contact.html
│ └── main/
│ ├── register.html
│ └── login.html
├── health_app/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── manage.py
├── db.sqlite3
├── requirements.txt
└── .gitignore

## Views

### Home View
Handles the nutrition query and displays the results.

### Blog View
Fetches and displays blog posts from the JSONPlaceholder API.

### Contact View
Handles contact form submissions and stores the data in the database.

### Register View
Allows users to register a new account.

### Login View
Allows users to log in.

### Logout View
Logs out the user.

## Templates

- **home.html**: Form to submit a nutrition query and display results.
- **blog.html**: Displays a list of blog posts.
- **contact.html**: Form to submit contact information.
- **main/register.html**: Registration form.
- **main/login.html**: Login form.

## Models

### ContactMessage
Stores contact form submissions.

## Forms

### UserCreationForm
Standard Django form for user registration.

### AuthenticationForm
Standard Django form for user authentication.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Contact

For any inquiries or questions, please contact [abhiv5976@gmail.com.com].


