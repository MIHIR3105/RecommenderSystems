# 🛒 SmartCart Recommender System
This project implements a hybrid recommendation engine for an e-commerce platform using **Collaborative Filtering** and **Association Rule Mining** to recommend products and uncover purchase patterns from real interaction data.

---------------------------------------------------------------------------------------------------


## 📂 Project Structure
RECOMMENDERSYSTEMS/
│
├── ecommerce_user_data.csv          # Dataset of user-product interactions
├── product_details.csv              # Product metadata
├── project_notebook.ipynb           # Your main implementation notebook
├── README.md                        # Project overview and instructions
└── requirements.txt                 # Python dependencies for this project

---------------------------------------------------------------------------------------------------


## 📦 Dataset Description
### 1. `ecommerce_user_data.csv`

| Column          | Description                        |
|-----------------|------------------------------------|
| UserID          | Unique user identifier             |
| ProductID       | Unique product identifier          |
| Rating          | User's rating of the product (1–5) |
| ProductCategory | Category of the product            |
| Timestamp       | Time of interaction                |

### 2. `product_details.csv`

| Column      | Description              |
|-------------|--------------------------|
| ProductID   | Unique product ID        |
| ProductName | Name of the product      |
| Category    | Category (e.g., Electronics) |

---------------------------------------------------------------------------------------------------


## 🚀 How to Run the Project
### ✅ Prerequisites
Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend networkx
: You can use a virtual environment or Jupyter Notebook in VS Code.

---------------------------------------------------------------------------------------------------


🧠 Running the Project
Open enhanced_project_notebook.ipynb in Jupyter or VS Code.
Run all cells top to bottom.
You will see:
Cleaned and structured data
Cosine-based user similarity
Top-5 product recommendations
Evaluation using Precision@5
Frequent itemsets using Apriori
Association rule visualizations (bar chart & network graph)

---------------------------------------------------------------------------------------------------


🧪 Techniques Implemented
✅ Part 1: Data Preprocessing
Merged datasets, handled missing values
Built a user-item matrix
Created features: interaction count, average rating, user type

✅ Part 2: Collaborative Filtering
Cosine similarity between users
Recommended products based on most similar users
Evaluated recommendations with Precision@5

✅ Part 3: Association Rule Mining
Converted interactions into transactions
Applied Apriori algorithm (support ≥ 0.01)
Extracted and visualized strong rules using lift

✅ Part 4: Visual Analysis
Heatmap of user similarities
Bar chart of top frequent itemsets
Network diagram of association rules

---------------------------------------------------------------------------------------------------


📊 Key Visual Outputs
✅ User Similarity Heatmap
✅ Top-5 Product Recommendations (per user)
✅ Top Frequent Itemsets (bar chart)
✅ Association Rules (network diagram)

---------------------------------------------------------------------------------------------------


🧠 Conceptual Questions (covered in report.pdf)
How does data sparsity affect recommendations?
What product bundles were found via Apriori?
What improvements are recommended for real-world deployment?

---------------------------------------------------------------------------------------------------


🧾 Authors & Credits
Group Members:
Name               | Student ID | Email                         
-------------------|------------|------------------------------------------
Abhibhai Patel     | 40289176   | abhipatel120801@gmail.com
Yashesh Sorathia   | 40267022   | yashesh.sorathia@gmail.com
Mihir Panchal      | 40291315   | (email not provided)

---------------------------------------------------------------------------------------------------


📬 Feedback & Issues
For feedback or queries, please contact the team via
📧 abhipatel120801@gmail.com
📧 yashesh.sorathia@gmail.com
📧 XXXXXXXXXXXXXXXXXXXXXXXXX

---------------------------------------------------------------------------------------------------