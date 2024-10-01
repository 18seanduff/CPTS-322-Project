# CampusSafe

A cross-platform mobile application that provides features for notifying college students about various emergencies.

# Build and Run

Needed tools: npm, npx, and Python

## Frontend

Run these commands:

1. `cd frontend/CampusSafe`
2. `npm install`
3. `npx expo start`
4. Install Expo Go on device
5. Scan QR code with Expo Go

## Backend

Run these commands:

1. `python -m venv env`
2. To activate the virtual environment run:
   - Windows cmd: `env/Scripts/activate.bat`
   - Windows PowerShell: `env/Scripts/Activate.ps1`
   - Linux or macOS: `soruce env/bin/activate`
4. `pip install -r requirements.txt`
5. `cd campussafe`
6. `python manage.py runserver`
7. The server should now be running on `http://127.0.0.1:8000/` (or `http://localhost:8000/`)
