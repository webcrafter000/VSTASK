# Assignment for Workflow

This workflow is a cutting-edge platform that combines a React-based frontend with a FastAPI backend, designed to facilitate the creation and management of workflows through Directed Acyclic Graphs (DAGs).

## Screenshots
![vsassgn](https://github.com/user-attachments/assets/24451cd6-bcb3-4c4d-bdde-61147cd1bb2b)

![vsassign2](https://github.com/user-attachments/assets/9a3627cb-8e3b-4a48-831f-3bcda9cbf71c)

![vsassign3](https://github.com/user-attachments/assets/cefb5f91-8452-4913-a578-08871b465737)

## Key Features

- **React Frontend**: A sleek, modern, and responsive UI built with React.
- **DAG Integration**: Organize and manage workflows as Directed Acyclic Graphs (DAGs).
- **FastAPI Backend**: A lightweight, high-performance API built with FastAPI.


## Setup Instructions

### Prerequisites

- Node.js installed on your machine
- Python 3.7 or above
- FastAPI library

### Setting Up the Frontend

1. Navigate to the frontend folder:
    ```bash
    cd frontend
    ```
2. Install required dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```

### Setting Up the Backend

1. Navigate to the backend directory:
    ```bash
    cd backend
    ```
2. Set up a virtual environment:
    ```bash
    python -m venv venv
    ```
3. Activate the virtual environment:
    - For Windows:
        ```bash
        venv\Scripts\activate
        ```
    - For macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
4. Launch the FastAPI server:
    ```bash
    uvicorn main:app --reload
    ```

## Usage Instructions

1. Open your browser and visit `http://localhost:3000` to view the React frontend.
2. Use the interface to design and manage workflows.
3. The backend API will be accessible at `http://localhost:8000`.

