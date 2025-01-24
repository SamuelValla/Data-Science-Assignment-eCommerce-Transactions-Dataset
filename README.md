# ZeoTap Internship Assignment: Data Science Project  
**Author**: Samuel Valla  

## Project Overview  
This repository contains the solution to the **Data Science Assignment: eCommerce Transactions Dataset** provided by ZeoTap as part of the internship recruitment process. The goal of this project was to analyze eCommerce transaction data and build models for customer segmentation and lookalike recommendations. The project was completed with a focus on data exploration, clustering, and customer profiling.

---

## Repository Contents  
1. **`Samuel_Valla_Clustering.ipynb`**  
   - A Jupyter Notebook containing the code and steps for clustering analysis on the eCommerce dataset.  
   - The notebook includes the implementation of clustering techniques, calculation of the Davies-Bouldin Index (DB Index), and other metrics for cluster evaluation. It also includes visualizations to understand the formed clusters.

2. **`Samuel_Valla_Clustering.pdf`**  
   - A detailed report on clustering analysis, including metrics like DB Index and Silhouette Score, along with insights derived from the clustering results.  

3. **`Samuel_Valla_EDA.ipynb`**  
   - A Jupyter Notebook containing the Exploratory Data Analysis (EDA) performed on the eCommerce dataset.  
   - The notebook covers data cleaning, summary statistics, visualizations, and insights derived from customer, product, and transaction data.

4. **`Samuel_Valla_EDA.pdf`**  
   - The 5 business insights derived from the EDA as asked for.  

5. **`Samuel_Valla_Lookalike.csv`**  
   - The output file for the lookalike model, containing mappings of customer IDs to their top 3 similar customers and the associated similarity scores.  
   - **Format**: `Map<cust_id, List<cust_id, score>>`  

6. **`Samuel_Valla_Lookalike.ipynb`**  
   - A Jupyter Notebook containing the implementation of the lookalike model.  
   - The model uses both customer profile and transaction data to recommend the top 3 most similar customers for each input user.  

---

## Project Highlights  
- **Exploratory Data Analysis (EDA)**:  
   - Comprehensive cleaning and visualization of customer, product, and transaction datasets.  
   - Insights into customer regions, product popularity, and monthly transaction trends.  

- **Customer Segmentation (Clustering)**:  
   - Implementation of clustering algorithms with a focus on finding the optimal number of clusters.  
   - Evaluated clustering performance using Davies-Bouldin Index (DB Index) and Silhouette Scores.  
   - Visualized clusters using PCA for interpretability.  

- **Lookalike Modeling**:  
   - Built a model to identify the top 3 similar customers for each given customer based on profile and transaction history.  
   - Generated similarity scores for recommendations and exported results to a CSV file.  

---

## How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/<SamuelValla>/<Data-Science-Assignment-eCommerce-Transactions-Dataset>.git
   cd <Data-Science-Assignment-eCommerce-Transactions-Dataset>
