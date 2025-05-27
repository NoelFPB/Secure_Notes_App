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
 API Usage Examples
- `POST /register` — Register a new user
- `POST /login` — Log in and receive a JWT
- `GET /notes?token=...` — Retrieve notes
- `POST /notes?token=...` — Create a new note
- `DELETE /notes/<id>?token=...` — Delete a note

## Future work

- Add frontend interface for managing notes
- Token expiration and refresh logic
- Deployment to a public server
- Unit tests and input sanitization
