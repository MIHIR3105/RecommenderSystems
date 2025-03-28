# SmartCart Recommender System & Pattern Mining

## Overview
This project implements a recommender system using collaborative filtering and pattern mining techniques for an e-commerce dataset. The implementation covers:
- **Data Preprocessing**: Loading and cleaning datasets, creating a user-item matrix.
- **User-Based Collaborative Filtering**: Computing user similarity using cosine similarity and recommending products.

## Prerequisites
Ensure you have the following dependencies installed:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Running the Code
1. Place the dataset files (`ecommerce_user_data.csv` and `product_details.csv`) in the same directory as the notebook.
2. Open the Jupyter Notebook and run all cells sequentially.
3. The script will:
   - Load and clean the data.
   - Generate a user similarity heatmap.
   - Provide product recommendations for a sample user.

## Output
- **User Similarity Heatmap**: A visualization of user similarities.
- **Top Product Recommendations**: Displays recommended products for a sample user.
- **Processed Data**: User-item matrix and cleaned datasets.