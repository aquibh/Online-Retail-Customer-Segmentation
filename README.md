# Online Retail Customer Segmentation

This project analyzes an online retail dataset to segment customers based on their purchasing behavior. By applying RFM (Recency, Frequency, Monetary) analysis combined with K-Means clustering, it identifies distinct customer groups such as high-value, loyal, potential, and at-risk customers. These segments help businesses tailor marketing strategies, improve retention, and drive revenue growth.

---

## Key Features

- Data cleaning and preprocessing to ensure accuracy by removing missing values, invalid entries, and duplicates.  
- Feature engineering to compute Recency (days since last purchase), Frequency (number of unique invoices), and Monetary (total spend) per customer.  
- RFM scoring to rank customers into meaningful segments based on quartile distributions.  
- K-Means clustering on scaled RFM data to validate segments and discover natural groupings.  
- PCA-based visualization to illustrate cluster separation and support interpretability.  
- Business insights to prioritize marketing efforts on high-value and loyal customers, and to engage at-risk segments.

---

## Dataset

The dataset used is the [Online Retail dataset] from Kaggle, containing transactional data from a UK-based online retailer.

---


## Results and Insights

- Successfully segmented customers into distinct groups: high-value, loyal, potential loyalists, and at-risk, based on their purchasing behavior.  
- Clustering analysis confirmed natural groupings, enabling tailored marketing strategies for each segment.  
- Visualization through PCA provided clear separation of customer clusters, aiding business stakeholders in understanding segment characteristics.  
- Recommended targeted retention campaigns for loyal customers and re-engagement efforts for at-risk customers to boost customer lifetime value and reduce churn.

---

## Technologies Used

- Python  
- Pandas for data manipulation and cleaning  
- NumPy for numerical operations  
- Scikit-learn for clustering (K-Means) and preprocessing (scaling, PCA)  
- Matplotlib and Seaborn for data visualization  
- Google Colab for exploratory analysis and development  
