## Column-Transformer in Machine Learning ##

# Overview:-
-> This project demonstrates how to apply "multiple preprocessing steps" — such as "scaling numerical features" and "encoding categorical features" — using the "ColumnTransformer" in          Scikit-learn.  
-> It includes two parts:
   1. "Without ColumnTransformer:" Manual preprocessing of each column  
   2. "With ColumnTransformer:" Streamlined and automated feature transformation  


# Objectives:-
-> Understand the role of **ColumnTransformer** in data preprocessing  
-> Compare manual preprocessing vs. ColumnTransformer approach  
-> Learn how to combine "StandardScaler" and "OneHotEncoder" in one step  
-> Prepare data efficiently for machine learning models  


# Techniques / Concepts Used:-
-> `ColumnTransformer` from `sklearn.compose`  
-> `StandardScaler` for numerical features  
-> `OneHotEncoder` for categorical features  
-> `make_column_selector` and `make_column_transformer`  
-> Integration with Scikit-learn’s pipeline  


# Dataset:-
-> A dataset containing both **numerical** and **categorical** columns was used to demonstrate how to process each type of feature correctly before model training.


# Implementation Steps
## Without ColumnTransformer:-
-> Manually apply scaling to numeric columns using `StandardScaler`  
-> Manually encode categorical columns using `OneHotEncoder`  
-> Combine them into a single DataFrame  

## With ColumnTransformer:-
-> Define preprocessing for each column type  
-> Use `ColumnTransformer` to apply transformations simultaneously  
-> Output a ready-to-use transformed dataset  


# Key Observations:-
-> Manual preprocessing is repetitive and prone to errors.  
-> ColumnTransformer makes preprocessing **clean, scalable, and reusable**.  
-> It’s essential for real-world ML pipelines and model deployment.  


# Conclusion:-
-> The "ColumnTransformer" simplifies preprocessing by handling different feature types efficiently within a single transformation pipeline.  
-> It’s a key step toward building "production-ready ML workflows".


# Technologies Used:-
-> Python 
-> NumPy  
-> Pandas  
-> Scikit-learn  
-> Matplotlib  
-> Seaborn  
