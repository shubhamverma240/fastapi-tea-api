# FastAPI Tea API 🍵

A beginner-level REST API project built using **Python and FastAPI** as part of my FastAPI crash course.

The project demonstrates basic API development and CRUD operations using HTTP methods.

## Tech Stack
- Python
- FastAPI
- Pydantic
- Uvicorn

## Features
- **GET** – Retrieve all tea records.
- **POST** – Add a new tea.
- **PUT** – Update an existing tea.
- **DELETE** – Delete a tea record.
- **Pydantic** – Validate incoming data using BaseModel.

## Run Locally

Install dependencies:

```bash
pip install fastapi uvicorn
```

Start the server:

```bash
python -m uvicorn main:app --reload
```

Open the interactive API documentation:

http://127.0.0.1:8000/docs

## Project Structure

```text
fastapi-tea-api/
├── main.py
└── README.md
```

## What I Learned
- FastAPI application setup
- API routes and endpoints
- HTTP methods (GET, POST, PUT, DELETE)
- Pydantic models and data validation
- Handling API requests and responses

## Author

**Shubham Verma**

[GitHub](https://github.com/shubhamverma240) | [LinkedIn](https://www.linkedin.com/in/shubham-verma-624b5824a)
