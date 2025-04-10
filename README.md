# FastAPI Todo Server

This is a simple FastAPI application for managing a todo list.

The purpose of this repository is to illustrate the use of CI/CD practices using GitHub Actions and render.

## Features
- Create, read, update, and delete todos.
- Lightweight and easy to set up.

## Requirements
- Python 3.11 or higher
- `pip` (Python package manager)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/todo-server.git
    cd todo-server
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Server

1. Start the FastAPI server:
    ```bash
    uvicorn main:app --reload
    ```

2. Open your browser and navigate to:
    ```
    http://127.0.0.1:8000
    ```

3. Access the interactive API documentation at:
    ```
    http://127.0.0.1:8000/docs
    ```

## Project Structure
```
todo-server/
├── main.py          # Entry point of the application
├── models.py        # Database models
├── routes/          # API routes
├── requirements.txt # Python dependencies
└── README.md        # Project documentation
```

## License
This project is licensed under the MIT License.