# CampaignResponseModel

## 1. Import Dataset

1.1 Retail_Data_Response.csv

1.2 Retail_Data_Transactions.csv

## 2. Data Preparation

2.1 Create data set with RFM variables

2.2 Create data set with CLV variables

## 3. Calculating response rate

Data is imbalanced

![imbalanced data](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_3_Calculating%20response%20rate.JPG)

## 4. Creating train and test dataset

### 4.1 RFM

![RFM](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_4_1_RFM.JPG)

### 4.2 CLV

![CLV1](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_4_2_CLV_1.JPG)
![CLV2](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_4_2_CLV_2.JPG)
![CLV3](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_4_2_CLV_3.JPG)
![CLV4](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_4_2_CLV_4.JPG)

## 5. Fixing Imbalanced with SMOTE

### 5.1 Logistic Regression (SMOTE RFM & SMOTE CLV)

![Logistic Regression](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_5_1_Logistic%20Regression%20(SMOTE%20RFM%20%26%20SMOTE%20CLV).jpg)

### 5.2 XGBoost (SMOTE RFM & SMOTE CLV)

![XGBoost](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_5_2_XGBoost%20(SMOTE%20RFM%20%26%20SMOTE%20CLV).jpg)

## 6. Tune Model

XGBoost - SMOTE CLV

![XGBoost - SMOTE CLV](https://github.com/Ssureeporn/BADS7105_CRM/blob/main/Assignment04_CampaignResponseModel/04_6_XGBoost%20-%20SMOTE%20CLV.jpg)

## 7. Result Discussion

Tune Model with XGBoost model - SMOTE CLV and define max_depth=1, which the best with th following score.

AUC Score for training data = 0.7401

AUC Score for test data = 0.7359
