# TechHire API

A Django REST Framework API for tech job listings.

## Setup

```bash
# 1. Create and activate virtual environment
python -m venv venv
venv\Scripts\activate       # Windows
# source venv/bin/activate  # Mac/Linux

# 2. Install dependencies
pip install -r requirements.txt

# 3. Apply migrations
python manage.py migrate

# 4. (Optional) Seed sample data
python manage.py seed_data

# 5. Run the server
python manage.py runserver
```

## API Docs
Import `TechHire_API.postman_collection.json` into Postman to explore all endpoints.
