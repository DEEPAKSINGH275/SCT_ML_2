# Customer Segmentation using K-Means Clustering

## Overview
This project implements the **K-Means Clustering** algorithm to group customers of a retail store based on their purchasing behavior. The model segments customers into different clusters using their annual income and spending score.

## Objective
To build a clustering model that groups customers based on:
- Annual Income
- Spending Score

## Dataset
The project uses the **Mall Customers** dataset consisting of:

- `Mall_Customers.csv` – Contains customer details such as Customer ID, Gender, Age, Annual Income, and Spending Score.

## Features Used
- `Annual Income (k$)`
- `Spending Score (1-100)`

## Technologies Used
- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn

## Steps Performed
1. Imported the required Python libraries.
2. Loaded the customer dataset.
3. Selected Annual Income and Spending Score as the input features.
4. Trained the K-Means clustering model.
5. Assigned each customer to a cluster.
6. Visualized the customer segments using a scatter plot.

## Machine Learning Model
- K-Means Clustering

## Output
The model groups customers into **5 different clusters** based on their purchasing behavior. A scatter plot is generated to visualize the customer segments along with their cluster centroids.

## Project Structure
```
├── Mall_Customers.csv
├── Customer_Segmentation.ipynb
└── README.md
```

## Requirements
Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

## How to Run
1. Upload `Mall_Customers.csv` to Google Colab.
2. Run all the cells in the notebook.
3. The notebook will generate customer clusters and display the visualization.

## Future Improvements
- Determine the optimal number of clusters using the Elbow Method.
- Perform feature scaling for improved clustering.
- Compare K-Means with DBSCAN and Hierarchical Clustering.
- Use additional customer features for better segmentation.

## Author
**Deepak Singh**

B.Tech Computer Science and Engineering  
Dr. B.R. Ambedkar National Institute of Technology (NIT) Jalandhar
