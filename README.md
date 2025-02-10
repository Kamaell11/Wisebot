# Wisebot

Wisebot is an advanced philosophical platform that combines artificial intelligence with classical philosophical texts. The goal of the project is to enable users to interact with chatbots trained on philosophical quotes, participate in quizzes, and explore an extensive database of quotes. Designed for students, educators, and curious minds, Wisebot makes philosophy accessible and fun through AI-powered learning and gamification.

## Features

- **Philosophical Chatbot** – Answers questions by quoting the thoughts of great philosophers.
- **Philosophical Quizzes**:
  - *"Who said it?"* – Guess the author of the quote.
  - *"Which philosopher am I?"* – Personality test.
- **Quote Search Engine** – Allows searching for quotes by philosopher, era, and topics.
- **Personalized Chatbots** – Interact with bots imitating specific philosophers (optional).

## User Roles

- **Student** – Basic user, can use the chatbot and quizzes.
- **Scholar** – Access to data analysis and statistics.
- **Tutor** – Lecturers, can add quotes, content, and lead debates.

## Installation and Setup

### 1. Prerequisites

- Python 3.10+
- PostgreSQL (or SQLite for testing)
- Git

### 2. Cloning the Repository

```bash
git clone https://github.com/twoje-repo/wisebot.git
cd wisebot
```

### 3. Creating a Virtual Environment
## Virtualenv

```bash
python3 -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate    # Windows
```

## Conda
```bash
conda create -n wisebot python=3.10
conda activate wisebot
```

## Installing Dependencies
```bash
pip install -r requirements.txt
```

## Database Configuration

Edit the .env file (create it based on .env.example):

```
DATABASE_URL=postgresql://user:password@localhost:5432/wisebot
SECRET_KEY=supersecretkey
DEBUG=True
```

Run database migrations:
```bash
python manage.py migrate
```

## Running the Application
```bash
python manage.py runserver
```

The application should be available at: http://127.0.0.1:8000

## Running with Docker (Optional)
```bash
docker-compose up --build
```

# TODO

    Add more features.

    Improve UI/UX.

    Expand the quote database.

# License

This project is licensed under the MIT License.
