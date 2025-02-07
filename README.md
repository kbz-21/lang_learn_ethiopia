# Ethiopian Language Learning Platform

## Overview
The **Ethiopian Language Learning Platform** is a web-based application designed to help users learn Ethiopian languages such as Amharic, Oromo, and Tigrinya. It offers interactive lessons, quizzes, and gamified learning experiences to enhance language acquisition.

## Features
- User authentication (registration, login, and profile management)
- Interactive lessons and exercises
- Speech recognition for pronunciation practice
- Gamified learning with points, badges, and leaderboards
- Multi-language support (Amharic, Oromo, Tigrinya, etc.)
- Progress tracking and performance analytics

## Technologies Used
- **Back-end**: Django (Python)
- **Front-end**: React/Vue (JavaScript)
- **Database**: PostgreSQL/MySQL
- **Authentication**: JWT, Django Authentication
- **APIs**: Text-to-Speech (TTS), Speech Recognition

## Installation
### Prerequisites
- Python 3.x
- Django
- Virtual environment (venv or virtualenv)
- PostgreSQL/MySQL database setup

### Setup Steps
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/ethiopian-language-learning.git
   cd ethiopian-language-learning
   ```
2. **Create and activate a virtual environment**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Configure environment variables** (Create a `.env` file and set necessary keys)
   ```sh
   SECRET_KEY=your_secret_key
   DEBUG=True
   DATABASE_URL=your_database_url
   ```
5. **Run database migrations**
   ```sh
   python manage.py migrate
   ```
6. **Create a superuser** (for admin access)
   ```sh
   python manage.py createsuperuser
   ```
7. **Start the development server**
   ```sh
   python manage.py runserver
   ```
8. **Access the application**
   Open `http://127.0.0.1:8000/` in your browser.

## API Endpoints (if applicable)
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | /api/lessons/ | Retrieve all lessons |
| POST | /api/lessons/ | Create a new lesson |
| GET | /api/lessons/{id}/ | Retrieve lesson details |
| POST | /api/progress/ | Track user progress |

## Contribution
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions or contributions, reach out to [your email or GitHub profile].
