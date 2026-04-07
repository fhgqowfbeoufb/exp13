# exp13

AIM

To study and implement data preprocessing techniques in Python using Pandas and Scikit-learn for cleaning, transforming, and preparing datasets for analysis and machine learning.

THEORY

Data preprocessing is a crucial step in data analysis and machine learning, where raw data is refined and converted into a structured format suitable for further processing. Real-world datasets are often incomplete, inconsistent, or unstructured, containing missing values, duplicate records, categorical data, and numerical features with different scales.

Python libraries such as Pandas and Scikit-learn provide efficient tools to address these challenges. Key preprocessing steps include handling missing data, removing duplicates, encoding categorical variables into numerical form, scaling numerical features, and dividing the dataset into training and testing sets. Proper preprocessing enhances data quality and significantly improves the performance and accuracy of machine learning models.

One-line Explanation of Functions Used
read_csv() – Loads data from a CSV file into a DataFrame.
isnull() – Detects missing values in the dataset.
sum() – Calculates the total count of missing or duplicate values.
fillna() – Replaces missing values with specified statistics (mean, median, or mode).
dropna() – Removes rows or columns containing missing values.
duplicated() – Identifies duplicate entries in the dataset.
drop_duplicates() – Eliminates duplicate records.
LabelEncoder() – Converts categorical labels into numerical values.
get_dummies() – Performs one-hot encoding by creating binary columns.
StandardScaler() – Normalizes numerical data to have zero mean and unit variance.
train_test_split() – Divides the dataset into training and testing subsets.
info() – Provides a summary of the dataset, including data types and structure.
CONCLUSION

In this experiment, we successfully explored and implemented essential data preprocessing techniques using Pandas and Scikit-learn. We learned how to clean and prepare raw data by handling missing and duplicate values, encoding categorical variables, scaling numerical features, and splitting datasets. These steps are fundamental for improving data quality and ensuring better performance of machine learning models.
