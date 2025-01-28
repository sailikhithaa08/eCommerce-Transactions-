# eCommerce Transactions Analysis

This project involves the analysis of eCommerce transactions data, where the goal is to explore, segment customers, and identify lookalike profiles based on transactional behavior. The project is divided into several tasks:

## Project Overview
The eCommerce transactions dataset includes customer and transaction information. The analysis is performed using the following tasks:
1. **Exploratory Data Analysis (EDA)**: Data exploration, visualizations, and insights extraction.
2. **Lookalike Model**: Identifying customers that are similar based on transaction patterns.
3. **Customer Segmentation (Clustering)**: Grouping customers into segments based on their purchasing behavior using clustering algorithms.

## Tasks

# Exploratory Data Analysis (EDA)
In this part of the project, we explore the eCommerce transaction data and customer profiles. The goal is to identify patterns, trends, and insights that help in better understanding the customer base. Key visualizations and statistical analyses were used to highlight the most significant findings.

**Deliverables:**
- `Andraju_Sai_Likhitha_EDA.pdf`: A PDF report summarizing the EDA findings.
- `Andraju_Sai_Likhitha_EDA.ipynb`: Jupyter notebook containing the code for the EDA process.

### 2. Lookalike Model
This task focuses on finding similar customers based on their purchasing behavior. We combine customer data and transaction data to aggregate the total spend, product preferences, and transaction history. Using similarity metrics like Cosine Similarity, we identify the top 3 lookalike customers for each individual.

**Deliverables:**
- `Andraju_Sai_Likhitha_Lookalike.csv`: CSV file containing the top 3 similar customers for each customer with their respective similarity scores.
- `Andraju_Sai_Likhitha_Lookalike.ipynb`: Jupyter notebook containing the code for the lookalike model.

### 3. Customer Segmentation (Clustering)
Customer segmentation is done using clustering algorithms like K-Means and DBSCAN. The goal is to group customers into distinct segments based on their purchasing behavior. We use techniques like the Elbow Method, Silhouette Score, and DB Index to determine the optimal number of clusters and evaluate the clustering quality. The segmentation is then visualized using scatter plots and pair plots to highlight customer groups.

**Deliverables:**
- `Andraju_Sai_Likhitha_Clustering.pdf`: A PDF report summarizing the clustering results, visualizations, and insights.
- `Andraju_Sai_Likhitha_Clustering.ipynb`: Jupyter notebook containing the code for customer segmentation.

## Setup Instructions

To run the project, you will need to install the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- fpdf
- scipy

You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn fpdf scipy
