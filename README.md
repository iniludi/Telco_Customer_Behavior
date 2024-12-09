# Telco Customer Behavior

This repo contains all the code used for the IDA course final project, "Telco Customer Behavior".

## Project summary: 

Churn is one of the aspects that can lead to revenue losses. Predicting churn and understanding the factors that contribute to customer churn is important to reduce the churn rate. Utilizing clustering techniques, such as k-means and hierarchical clustering, along with churn prediction results can reveal significant patterns in customer behavior and characteristics that correlate with higher churn rates. By accurately predicting churn and understanding the underlying factors that contribute to it, we can implement customer retention strategies, reducing churn rates and associated revenue losses. Additionally, insights gained from clustering analysis can inform marketing strategies, customer service improvements, and product that fitted to different segments.

## Dataset:

The dataset used in this project is the Telco Customer Churn dataset, containing 7,043 records and 21 features (https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The features include customer demographics, service usage, billing details, and churn status.

## Code Setup and Requirements
Install all the required packages using the following command:
```
    $ pip install -r requirements.txt
```

## Files:

- `dataset`: Directory containing the telco customer churn dataset.
- `telco_customer_clustering.ipynb`: Script for extracting the features and implementing clustering methods.
- `....ipynb`: Script for explanatory data analysis and implementing predictive models.

## Clustering Results:

I used four different methods for clustering: Hierarchical (Agglomerative) Clustering with PCA, Hierarchical (Agglomerative) Clustering with t-SNE, K-Means Clustering with PCA, and K-Means Clustering with t-SNE.
The results are as follow:

#### 1. Hierarchical (Agglomerative) Clustering with PCA
<img src="https://github.com/user-attachments/assets/506b6eae-b788-4fef-a87b-0de003bfd66d" alt="dendrogram_ac_pca" width=75% height=75%/>
<img src="https://github.com/user-attachments/assets/9f97e1a4-4fda-4275-98ab-fb16cc1df569" alt="clusters_ac_pca" width=75% height=75%/>

#### 2. Hierarchical (Agglomerative) Clustering with t-SNE
<img src="https://github.com/user-attachments/assets/b531fbf6-ebb9-4641-863e-3ed117a81950" alt="dendrogram_ac_tsne" width=75% height=75%/>
<img src="https://github.com/user-attachments/assets/6e30e376-808f-4ef5-98ae-ef2d45c5302c" alt="clusters_ac_tsne" width=75% height=75%/>

#### 3. K-Means Clustering with PCA
<img src="https://github.com/user-attachments/assets/bfc72147-b749-401b-83c5-994bd4f5dd6b" alt="clusters_kmeans_pca" width=75% height=75%/>

#### 4. K-Means Clustering with t-SNE
<img src="https://github.com/user-attachments/assets/b28e26e1-66e1-47cb-92a0-a8a6691d26de" alt="clusters_kmeans_tsne" width=75% height=75%/>

