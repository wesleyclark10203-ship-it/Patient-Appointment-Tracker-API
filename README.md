# Patient-Appointment-Tracker-API
A FastAPI-based Patient Appointment Tracker API that allows users to create, view, update, and delete patient appointment records. It uses SQLite for local data storage and SQLAlchemy for database management.

## Run locally

```bash
uvicorn main:app --reload
```

Open:

- API: http://127.0.0.1:8000
- Docs: http://127.0.0.1:8000/docs

## Deploy

Deploy the project folder to a Python web host and use this start command:

```bash
uvicorn main:app --host 0.0.0.0 --port $PORT
```

The required deployment files are:

- `requirements.txt` for Python packages
- `Procfile` for hosts that detect the web start command automatically
- `.gitignore` to keep `venv/`, `__pycache__/`, and the local SQLite database out of Git
