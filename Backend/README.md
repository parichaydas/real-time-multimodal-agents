# Backend

This folder contains the backend services for the project.

Prerequisites
- Python 3.10+
- (optional) Docker

Local setup

1. Create a virtual environment:

```
python -m venv .venv
```

2. Activate it (Windows PowerShell):

```powershell
.\.venv\Scripts\Activate.ps1
```

3. Install dependencies (create `requirements.txt` if missing):

```powershell
pip install -r requirements.txt
```

Run (example)

- If using FastAPI/Starlette + Uvicorn:

```powershell
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

Tests

```powershell
pytest tests
```

Notes
- Add environment variables to a `.env` or use your deployment secrets manager.
- Populate `requirements.txt` with the backend dependencies.
