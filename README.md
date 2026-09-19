# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.

## Project Structure

* **frontend/**: Contains the Streamlit application code.
* **backend/**: Contains the FastAPI backend server code.
* **tests/**: Contains the test cases for both frontend and backend.
* **requirements.txt**: Lists the required Python packages.
* **README.md**: Provides an overview and instructions for the project.

## Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Imdad719/Expense-management-system.git
   cd Expense-management-system
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the FastAPI server**:

   ```bash
   uvicorn backend.server:app --reload
   ```

4. **Run the Streamlit app**:

   Open another terminal and navigate to the frontend directory:

   ```bash
   cd frontend
   ```

   Then run:

   ```bash
   streamlit run app.py
   ```
