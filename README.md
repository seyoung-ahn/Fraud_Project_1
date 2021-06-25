# NYC Property Tax Fraud Detection

### Project Overview 
- This is a group project from *Fraud Analytics* course at Rady School of Management, UC San Diego.
- The purpose of the project is to identify unusual cases in a property assessment data.
- It focuses on building an unsupervised fraud model - a model that uses a dataset without the output label (Fraud or not Fraud  

### Dataset 
- Used a real-world dataset that was prepared by the New York City government in 2010. 
- The dataset contains over 1 million records and 32 fields including each property's address, owner, lot size and building size. 

### Methods
- EDA and Data Cleaning
- Feature Engineering: created 48 candidate variables using the property charactertics that help determine unusualness
- Feature Selection: reduced the dimensionality of the feature matrix using principal component analysis (PCA)
- Fraud Algorithms: measuring unusualness using Z-scaling and autoencoder

### Conclusion
- Identified top 100 anomalous records based on the final fraud score
- Among the top 100, assessed 10 records that stand out from the list by searching each property using Google Map (Please refer to the project report for a detailed analysis) 

Author: Seyoung Ahn 

Date Completed: April 2021 
