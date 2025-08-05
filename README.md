# Doctor Advice App

A Flask-based web app for doctors to manage patients, give advice, and generate prescriptions as PDFs.

## Features
- Doctor registration and login
- Add/edit/delete patient advice
- Drug management (with JSON import/export)
- PDF prescription with QR code and digital signature block
- Deployable on Render.com

## Environment Variables
Create a `.env` file with the following:

```
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///local.db
```

## Virtual Environment Setup (Linux/macOS/Windows)

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Run App
```bash
flask run
```
