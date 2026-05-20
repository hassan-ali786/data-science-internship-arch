# Movie Rating Prediction using Linear Regression

## Project Overview
This project predicts **movie ratings** using user and movie IDs as input features with **Linear Regression**. It demonstrates a regression workflow for recommendation system tasks.

## Dataset
- **Source:** MovieLens Dataset (CSV)
- **Features Used:**
  - userId
  - movieId
- **Target:** rating

## Workflow
1. Load dataset using pandas
2. Prepare features and target variable
3. Split data into training and testing sets
4. Train Linear Regression model
5. Evaluate model using MAE, MSE, and R2 score
6. Visualize actual vs predicted ratings
7. Save trained model using joblib

## Tools & Libraries
- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Joblib

## File Structure
```
Movie-Rating-Prediction/
├── data/
│   └── ratings.csv
├── notebooks/
│   └── Movie_Rating_Prediction.ipynb
├── requirements.txt
└── README.md
```
## How to Run
1. Install required packages: `pip install -r requirements.txt`
2. Open the notebook `Movie_Rating_Prediction.ipynb`
3. Run all cells
4. Check outputs and visualizations

## Contact
Hassan Ali  
Aspiring Data Scientist  
GitHub: https://github.com/hassan-ali786  
