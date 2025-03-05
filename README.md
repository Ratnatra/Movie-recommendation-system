# Movie Recommendation System

## Description
The Movie Recommendation System is designed to provide users with personalized movie recommendations based on their preferences and viewing history. By leveraging advanced algorithms and data analysis techniques, this system aims to enhance the user experience by suggesting movies that they are likely to enjoy.

## Features
- Personalized movie recommendations
- User profile creation and management
- Viewing history tracking
- Movie rating and review system
- Search functionality for movies
- Recommendation algorithms using collaborative filtering and content-based filtering

## Technologies Used
- Programming Language: Python
- Framework: Django
- Database: PostgreSQL
- Frontend: HTML, CSS, JavaScript
- Machine Learning: Scikit-learn, Pandas, NumPy

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Ratnatra/Movie-recommendation-system.git
    ```
2. Change to the project directory:
    ```bash
    cd Movie-recommendation-system
    ```
3. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Set up the database:
    ```bash
    python manage.py migrate
    ```
6. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```
7. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage
1. Open your web browser and navigate to `http://127.0.0.1:8000/`.
2. Register a new account or log in with your existing credentials.
3. Browse and rate movies to improve the accuracy of the recommendations.
4. View personalized movie recommendations on your dashboard.

## Contribution
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details..
