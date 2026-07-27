# Summary Report

## Mall Shopper Profiling using Unsupervised Machine Learning

### Business Problem and Dataset

Shopping malls collect customer information but often do not know how to
group customers based on purchasing behavior. This project uses the Mall
Customers dataset (200 records) with CustomerID, Gender, Age, Annual
Income (k\$), and Spending Score (1--100) to discover meaningful
customer segments using unsupervised learning.

### Features Used for Clustering

Two feature sets were used. The 2D feature set contained Annual Income
and Spending Score for clear visualization. The second feature set
contained Age, Annual Income, Spending Score, and encoded Gender, giving
richer customer profiles after StandardScaler normalization.

### Best Performing Algorithm

K-Means, Agglomerative Clustering, and DBSCAN were compared using
Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index.
K-Means produced the best balance of compact and well-separated clusters
while remaining easy to interpret for business use. Agglomerative
produced similar clusters, and DBSCAN was useful for detecting outliers.

### Shopper Segments

-   High Income--High Spending: Premium customers suitable for VIP
    offers.
-   High Income--Low Spending: Target with loyalty rewards and
    personalized promotions.
-   Low Income--High Spending: Encourage with discounts and bundle
    offers.
-   Low Income--Low Spending: Focus on value-based promotions.
-   Average Customers: Increase engagement with regular recommendations.

### Future Work

Future improvements include collecting purchase history, visit
frequency, and product preferences. Semi-supervised learning could
improve segmentation if labeled data becomes available. A real-time
persona tagging API for the mall app could automatically assign customer
segments and deliver personalized offers.
