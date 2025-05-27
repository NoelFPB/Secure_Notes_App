# Secure Notes App

A simple and secure web application for managing personal notes using Flask, JWT authentication, and SQLite.

## Features

- User registration and login
- JWT-based token authentication
- Create, view, and delete personal notes
- Each note includes a title, content, and timestamp
- Homepage with basic HTML and CSS using Flask templates

## Technologies Used

- Python 3
- Flask
- SQLite + SQLAlchemy
- PyJWT
- Werkzeug (for password hashing)
- HTML/CSS (Jinja2 templates)

## Project Structure

```
secure-notes-app/
├── app.py
├── models.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── requirements.txt
└── README.md
```

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/secure-notes-app.git
cd secure-notes-app
```

2. Create a virtual environment (optional)
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run the application
```bash
python app.py
```

5. API Usage Examples
- `POST /register` — Register a new user
- `POST /login` — Log in and receive a JWT
- `GET /notes?token=...` — Retrieve notes
- `POST /notes?token=...` — Create a new note
- `DELETE /notes/<id>?token=...` — Delete a note

## Possible Improvements

- Add frontend interface for managing notes
- Token expiration and refresh logic
- Deployment to a public server
- Unit tests and input sanitization

## Author

Noel Francisco Prado Bucaro  
GitHub: https://github.com/yourusername
