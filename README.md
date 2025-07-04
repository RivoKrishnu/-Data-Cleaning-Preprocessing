# Data Preprocessing


This project demonstrates a basic data preprocessing pipeline using the Titanic dataset. It covers essential steps including handling missing values, encoding categorical variables, feature scaling, and outlier detection.

Steps Covered
1. Import and Explore Data
Load the dataset using pandas

Inspect data types and missing values

View summary statistics

2. Handle Missing Values
Replace missing Age values with the median

Fill missing Embarked values with the most frequent category

Drop Cabin column due to excessive missing values

3. Encode Categorical Features
Convert Sex and Embarked columns to numerical using one-hot encoding

4. Normalize Numerical Features
Use StandardScaler to scale Age and Fare columns

5. Visualize and Remove Outliers
Use boxplots to visualize outliers

Remove outliers based on the IQR (Interquartile Range) method

📦 Libraries Used
pandas

numpy

seaborn

matplotlib

scikit-learn
