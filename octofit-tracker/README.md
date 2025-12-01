OctoFit Tracker (scaffold)
==========================

This folder contains the scaffold for the OctoFit Tracker application.

Goals
- User authentication and profiles
- Activity logging and tracking
- Team creation and management
- Competitive leader board
- Personalized workout suggestions

Structure
```
octofit-tracker/
├── backend/
│   ├── venv/
│   ├── requirements.txt
└── frontend/
```

Ports used by the project
- `8000` : Django backend (public)
- `3000` : Frontend dev server (public)
- `27017`: MongoDB (private)

Quick start (Linux / bash)

Create the Python virtual environment and install backend requirements:

```bash
python3 -m venv octofit-tracker/backend/venv
source octofit-tracker/backend/venv/bin/activate
pip install -r octofit-tracker/backend/requirements.txt
```

Scaffold the frontend (example using Create React App):

```bash
npx create-react-app octofit-tracker/frontend
```

Notes
- Follow the detailed backend setup in `octofit-tracker/backend/README.md`.
- This repository follows the project instructions included in the `.github/instructions` folder.
