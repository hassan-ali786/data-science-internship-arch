# Customer Segmentation using KMeans

## Project Overview
This project segments customers based on their **Annual Income** and **Spending Score** using **KMeans clustering**. It helps businesses identify customer groups for targeted marketing and better decision-making.

## Video Demo:

https://github.com/user-attachments/assets/9dcb191f-427a-4a96-aff5-ae200dd08ef3

## Dataset
- **Source:** Mall Customers Dataset (CSV)
- **Features Used:**
  - Annual Income (k$)
  - Spending Score (1-100)

## Workflow
1. Load dataset using pandas
2. Exploratory Data Analysis (EDA)
3. Feature scaling using StandardScaler
4. Determine optimal clusters using the Elbow Method
5. Train KMeans clustering model
6. Evaluate clusters using silhouette score
7. Visualize clusters
8. Save trained model using joblib

## Results
- Optimal clusters found: 5
- Silhouette Score indicates well-separated clusters
- Cluster visualization shows distinct customer groups

## Tools & Libraries
- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

## File Structure
```
Task-3-Customer-Segmentation/
├── data/
│ └── Mall_Customers.csv
├── notebooks/
│└── Customer_Segmentation.ipynb
├── requirements.txt
└── README.md

```

## How to Run
1. Install required packages: `pip install -r requirements.txt`
2. Open the notebook `Customer_Segmentation.ipynb`
3. Run all cells
4. Check outputs and visualizations

## Author
Hassan Ali 
Data Scientist  & Machine Learning Engineer
GitHub: https://github.com/hassan-ali786  
