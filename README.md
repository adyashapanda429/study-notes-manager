
# Study Notes Manager

A simple web application to organize and manage study notes.

## Features

- Add new study notes
- View saved notes
- Edit existing notes
- Delete notes
- Search notes by title or content
- Sort notes by newest, oldest, or title
- Validate note inputs
- Save notes in an SQLite database
- Display note creation dates

## Technologies Used

### Frontend
- Angular
- HTML
- CSS
- TypeScript

### Backend
- Python
- FastAPI
- SQLAlchemy
- SQLite

## Project Structure

- `frontend/` - Angular user interface
- `backend/` - FastAPI backend and database code
- `backend/requirements.txt` - Python package requirements

## How to Run the Project

### 1. Start the Backend

Open a terminal in the `backend` folder, activate your Python virtual environment, and run:

```bash
python -m uvicorn main:app --reload
```

Backend URL: http://127.0.0.1:8000

API documentation: http://127.0.0.1:8000/docs

### 2. Start the Frontend

Open another terminal in the `frontend` folder and run:

```bash
npm start
```

Frontend URL: http://localhost:4200

## Database

The project uses SQLite to store study notes so they remain available after restarting the application.

## Purpose

This project helps me learn how frontend applications, backend APIs, and databases work together.
