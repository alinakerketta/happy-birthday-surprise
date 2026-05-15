# Happy Birthday Surprise

A small Flask app that displays a birthday balloon and celebration animation.

## Project structure

- `backend.py` - Flask application entrypoint
- `templates/index.html` - HTML template for the birthday surprise page
- `static/style.css` - page styling
- `requirements.txt` - Python dependencies
- `.gitignore` - local files to exclude from Git commits

## Setup

1. Create and activate a Python virtual environment:
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```

## Run locally

```powershell
python backend.py
```

Then open `http://127.0.0.1:5000` in your browser.

## Run with Waitress

```powershell
.\.venv\Scripts\python.exe -m waitress --host 127.0.0.1 --port 5000 backend:app
```

## Notes

- `.gitignore` is optional, but helpful for excluding local environment files.
- No license file has been added per request.
