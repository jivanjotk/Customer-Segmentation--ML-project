# Customer-Segmentation for Life Insurance Analysis using Customer Credit Card Data --ML-project


## Introduction:
This project aims to develop a customer segmentation model to provide personalized recommendations for financial products such as saving plans, loans, and wealth management. The segmentation is based on the usage behavior of approximately 9000 active credit card holders over the last 6 months. The dataset contains 18 behavioral variables per customer.
## Aim:-
The business problem selected is related to market segmentation, which in turn aggregation of potential buyers into groups or segments, who have similarities in requirements and who would respond equally to a marketing activity, which could be a promotion or an offer. Market segmentation allows insurance companies to target diverse categories of customers who would identify products and services separately from one another. The data has been acquired from an open-sourced database, which is a customer’s credit card information. It is transactional data related to different customers’ credit cards with 18 behavioral variables.

## Data Description:
The dataset summarizes the usage behavior of active credit card holders and is provided at the customer level. It includes 18 behavioral variables.

## Data Source:
The dataset can be downloaded from [here](https://github.com/jivanjotk/Customer-Segmentation--ML-project/blob/main/Customer%20Data.csv)

## Algorithms Used:
K-Means Clustering: Divides the dataset into K clusters based on the mean values of variables.

**Steps Taken:**

1. **Data Preprocessing:**
   - Cleaned the dataset to handle missing values, outliers, and irrelevant variables.
   - Scaled the dataset for better performance.

2. **Dimensionality Reduction:**
   - Utilized dimensionality reduction techniques such as PCA (Principal Component Analysis) to reduce the number of features while retaining important information.

3. **Hyperparameter Tuning:**
   - Used the elbow method to find the optimal number of clusters (K=4) for K-Means clustering.

4. **Model Training:**
   - Trained the K-Means clustering model using the identified optimal number of clusters.
   - Found the cluster centers for each segment.

5. **Model and Data Persistence:**
   - Saved the trained K-Means model and the scaled dataset using joblib for future use.

6. **Model Evaluation:**
   - Used a decision tree classifier to evaluate the model's accuracy.
   - Split the data into training and testing sets.
   - Trained the decision tree classifier on the training data.
   - Tested the accuracy of the model on the testing data.
   - Saved the trained decision tree model for future use.




## Links :
I've shared all the necessary files, datasets, and workbooks above. Please feel free to use these resources for your upcoming projects. If you find value in this project , consider giving it a star or simply let me know. Your feedback would be greatly appreciated!

[Connect with me on LinkedIn 🌐](https://www.linkedin.com/in/jivanjot-kaur-993220262/) :)
