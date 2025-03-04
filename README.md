# Best Play Option Predictor

## Overview
This project is a machine learning-powered best play option predictor for NFL games. It utilizes 
niche algorithms to analyze team active players, gather stats from the last four years, and process 
every game's play-by-play data. The model predicts the best play option based on these insights.

## Repository Structure

### 1. **Database Connections**
- Connects to a MySQL database.
- Stores and retrieves historical player stats and game play-by-play data.
- Uses Python libraries such as `mysql-connector-python` for database interaction.

### 2. **SQL Queries**
- Processes raw data using SQL queries.
- Utilizes `numpy` and `pandas` for data manipulation and analysis.
- Extracts relevant features for model training and predictions.

### 3. **Machine Learning with PyTorch**
- Implements machine learning models using `PyTorch`.
- Trains and deploys models using AWS S3 and AWS SageMaker.
- Evaluates player performance and play effectiveness to predict the optimal play.

### 4. **API Connections**
- Backend is written in Python using `Flask`.
- Serves predictions and processed data to the frontend.
- Provides endpoints for retrieving player stats, play stats, and model predictions.

## Technologies Used
- **Database:** MySQL
- **Backend:** Flask (Python)
- **Machine Learning:** PyTorch, AWS SageMaker, AWS S3
- **Data Processing:** NumPy, Pandas
- **API:** RESTful API with Flask

## Getting Started
### Installation
```bash
# Clone the repository
git clone https://github.com/your-repo/best-play-predictor.git
cd best-play-predictor

# Install dependencies
pip install -r requirements.txt
```

### Running the Application
```bash
# Start the Flask API
python app.py
```

### Usage
- Call the API endpoints to get predictions.
- Connect the frontend to retrieve play recommendations.
- Use the database to analyze and store player stats.

## Future Improvements
- Enhance model accuracy with additional player performance metrics.
- Optimize database queries for faster data retrieval.
- Expand frontend integration for interactive play visualization.

---
This project aims to revolutionize NFL play predictions using advanced machine learning and data analytics. 🚀
