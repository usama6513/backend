# Backend API

This is a FastAPI backend application deployed on Hugging Face Spaces.

## Features
- FastAPI framework
- SQLite database
- Alembic migrations
- Docker support

## API Endpoints

The API will be available at: `https://usama6513-project.hf.space`

## Local Development

```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
uvicorn src.main:app --reload
```

## Deployment

This application is automatically deployed to Hugging Face Spaces when changes are pushed to the main branch of the GitHub repository.# Testing automatic deployment
