# Online Store Customer Segmentation

Customer segmentation of a UK online gift store (UCI Online Retail dataset, 541,909 transactions
from December 2010 to December 2011) using RFM features: recency, frequency and monetary value.

- Cleaning: missing customer IDs, duplicates, returns and service transactions removed.
- EDA: sales by country, seasonality by month, orders by hour of day.
- Models compared: KMeans, agglomerative clustering, Gaussian mixture and DBSCAN, scored with
  silhouette, Calinski-Harabasz and Davies-Bouldin.
- Final model: KMeans with k=3 (silhouette 0.491 ± 0.005 over 5 folds). DBSCAN scored higher on
  silhouette but produced unstable clusters.
- Result: three segments (regular, inactive and best customers) with a marketing strategy for each.

- Notebook: [01_customer_segmentation_rfm.ipynb](01_customer_segmentation_rfm.ipynb)
- Tools: pandas, scikit-learn, SciPy, Plotly

[Описание на русском](README.ru.md)
