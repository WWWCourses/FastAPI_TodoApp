# FastAPI Todo App

## Introduction

This project is a simple Todo application built with FastAPI. It allows users to add, update, and delete todo items. This app demonstrates the fundamental concepts of FastAPI.

## Features

- Add todo items
- Update the completion status of todo items
- Delete todo items

## Setup and Installation

### Requirements

- Python 3.x
- FastAPI and Uvicorn for async web serving
- python-multipart for parsing multipart/form-data
- Jinja2 for templates
- SQLAlchemy for database interactions
- sqlalchemy2-stubs for better type hinting with SQLAlchemy

### Creating a Virtual Environment

To isolate the project dependencies, it's recommended to create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Unix or MacOS
.\venv\Scripts\activate  # On Windows
```

### Installing Dependencies

Install FastAPI and other necessary packages from the requirements.txt file:

```
pip install -r requirements.txt
```

## Running the Application

```
# navigate to src/ folder
cd src

# run the server
uvicorn app:app --reload
```

Access the application by navigating to http://localhost:8000/ in your web browser.

You can access the API documentation automatically generated by FastAPI by visiting http://localhost:8000/docs in your web browser.
