# Expense Management Analysis

This project is an expense management Analysis that consists of a Streamlit frontend application and a FastAPI backend server.

## Key Features

- **Expense Tracking**: Add, update, and delete expenses with categories for better organization.
- **Data Visualization**: Charts and graphs to visualize spending trends.
- **Monthly Analytics**: Analyze expenses on a monthly basis to identify patterns and insights.
- **Budgeting Tools**: Set budgets for different categories and monitor spending against them.
- **Export Functionality**: Export data in formats like CSV and PDF for offline analysis.

## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
