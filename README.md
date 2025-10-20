# Task-1-Data-cleaning-and-preprocessing
In this repository , the data cleaning and preprocessing steps like finding the missing and values, standardizing the data, and removing the null values.

In the first step, import the basic libraries like pandas and numpy for the numerical purpose and pandas for reading the dataset.

In the second step, df = pd.read_csv('/content/amazon.csv'). This code is used to read the dataset.

In the third step, we came to know about the dataset columns and rows by this code( df.head()).

In the fourth step, basic information like the feature, the columns, the datatypes and others.

Then we have the data cleaning and preprocessing section in which 
-identifying the null values and missing values: df.isnull().sum() is used.
-handling the null values and missing values: df.fillna(0,inplace=True) is used.
-standardize the names: df.columns = df.columns.str.lower() is used.
-shape of dataset: df.shape is used.

saved the cleaned dataset
