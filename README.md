# Password Manager

A desktop password manager built with Python and Tkinter, for generating, saving, and retrieving website login details.

## What it does

- Generates strong random passwords (mix of letters, numbers, and symbols) and copies them straight to the clipboard
- Saves website, email/username, and password entries to a local file
- Looks up saved credentials by website name
- Simple GUI built with Tkinter, so no command-line interaction needed

## How it works

- **`main.py`** — handles the GUI, password generation logic, and read/write operations for saved credentials
- Credentials are stored locally in a JSON file, with each website mapped to its associated email and password
- Uses `pyperclip` to copy generated passwords directly to the clipboard for convenience

## Tech used

- Python 3
- Tkinter (GUI)
- JSON (local data storage)
- pyperclip

## What I'd improve next

- **Encrypt stored passwords** rather than saving them in plaintext — currently the biggest limitation, and something I'd prioritise fixing first if extending this project
- Add password strength validation and duplicate-website handling
- Replace the local JSON file with a proper database (e.g. SQLite) for more robust storage
- Add the ability to delete or edit existing saved entries

## Background

Built as part of a 100 Days of Code Python bootcamp, while working toward a software engineering internship.
