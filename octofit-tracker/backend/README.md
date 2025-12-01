OctoFit Tracker — Backend Setup
================================

This README describes the initial backend environment setup for OctoFit Tracker.

Create a Python virtual environment (recommended):

```bash
python3 -m venv octofit-tracker/backend/venv
source octofit-tracker/backend/venv/bin/activate
```

Install dependencies:

```bash
pip install -r octofit-tracker/backend/requirements.txt
```

Notes and constraints from the project instructions:
- Use Django's ORM for database interactions (do not run direct MongoDB scripts to create the DB schema).
- To check if `mongod` is running, use `ps aux | grep mongod`.
- `mongodb-org` is the recommended MongoDB server package and `mongosh` is the official client.

Next steps
- Run `django-admin startproject octofit_tracker octofit-tracker/backend` to create the initial Django project, or use the provided project files if added later.
