# Customer_Segmentation

## 1. Import Dataset

“Supermarket Dats.csv”

## 2. Prepare customer single view

Calculate features

![Calculate features](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment02_Customer_Segmentation/02_2_Calculate%20features.JPG)

## 3. Compare model performance

![Compare model performance](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment02_Customer_Segmentation/02_3_Compare%20model%20performance.JPG)

## 4. Spectral Clustering 

### 4.1 Cluster PCA Plot

![PCA Plot](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment02_Customer_Segmentation/02_4_1_Cluster%20PCA%20Plot.JPG)

### 4.2 Distortion Score Elbow for K-means Clustering

![Score Elbow](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment02_Customer_Segmentation/02_4_2_Distortion%20Score%20Elbow%20for%20K-means%20Clustering.JPG)

### 4.3 Number of Customer of Each Clustering

![Number of Clustering](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment02_Customer_Segmentation/02_4_3_Number%20of%20Customer%20of%20Each%20Clustering.JPG)

### 4.4 Silhouette Plot of K-Means Clustering for 6100 Samples in 4 Centers

![Silhouette Plot](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment02_Customer_Segmentation/02_4_4_Silhouette%20Plot%20of%20K-Means%20Clustering%20for%206100%20Samples%20in%204%20Centers.JPG)

## 5. Result Discussion

### cluster0 (Looker Customers):  Low total spend, Lowest recency and avg time between visit 

Recommend :

1. Run analysis on the cost vs revenue of offering promotions

2. Churn prediction (Lead scoring)

### cluster1 (So-so):  Average total spend, Recency and avg time between visit 

Recommend :

1. Daily promotion special

2. Discount special products, BOGO

### cluster2 (Royal):  Highest total spend, Highest Recency, Lowest avg between visit

Recommend : 

1. New products

2. promotion แนะนำเพื่อนเพิ่มได้รับส่วนลด

### cluster3 (Richer Customers):  High total spend, High Recency, Low avg between visit 

Recommend :

1. upsell 

2. voucher เมื่อซื้อครบสินค้าในแต่ละเดือบครบตามจำนวนเงินที่กำหนด 
