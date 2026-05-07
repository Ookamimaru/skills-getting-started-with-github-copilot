# Project Guidelines

## Code Style
Python 3.13 with FastAPI for backend, vanilla JavaScript/HTML/CSS for frontend. Reference [src/app.py](src/app.py) for API patterns and [src/static/](src/static/) for client-side code.

## Architecture
Simple FastAPI application with in-memory data storage. Activities endpoint at `/activities` with signup sub-endpoint. No persistence—data resets on restart. See [src/README.md](src/README.md) for API documentation.

## Build and Test
Install dependencies: `pip install -r requirements.txt`  
Run server: `python src/app.py` or `uvicorn src.app:app --reload`  
Test: `pytest` (add pytest to requirements.txt and create tests/ directory as needed)

## Conventions
Use email format `{name}@mergington.edu` for test data. Follow GitHub Skills exercise structure with steps in `.github/steps/` and workflows in `.github/workflows/`.