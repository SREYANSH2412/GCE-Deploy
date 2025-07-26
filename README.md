# FastAPI Hello World Application

A simple FastAPI backend application with a single GET endpoint that returns "Hello World".

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

### Option 1: Using uvicorn directly
```bash
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

### Option 2: Running the Python file directly
```bash
python main.py
```

## Testing the Endpoint

Once the server is running, you can test the endpoint by:

1. Opening your browser and visiting: http://localhost:8000
2. Using curl: `curl http://localhost:8000`
3. The response will be: `{"message": "Hello World"}`

## API Documentation

FastAPI automatically generates interactive API documentation:
- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc 