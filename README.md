# Data Cleaning & Feature Engineering on Titanic Dataset

## Overview
This mini project focuses on **data preprocessing**, a crucial step in any machine learning workflow. Using a standalone sample of the **Titanic dataset**, this project demonstrates key tasks such as:
- Handling missing values  
- Removing inconsistencies  
- Encoding categorical data  
- Creating new, meaningful features  

This project prepares the dataset for future machine learning tasks such as classification or regression.

---

## Objectives
- Clean and preprocess the Titanic dataset  
- Handle missing and inconsistent data  
- Encode categorical values into numerical format  
- Create new features to enhance model performance  
- Export the processed dataset for machine learning models  

---

## Project Structure

mini_project_3_titanic_cleaning/ │ ├── main.py                # Data cleaning & feature engineering code ├── requirements.txt       # Required Python libraries └── processed_data.csv     # Cleaned dataset (generated)

---

## Technologies Used
- Python  
- Pandas  
- NumPy  

---

## Installation & Setup

### Step 1 — Install dependencies
```bash
pip install -r requirements.txt

Step 2 — Run the project

python main.py

The cleaned dataset will be saved as processed_data.csv.


---

Data Cleaning Steps

1. Handle Missing Values

Filled missing Age values using median

Filled missing Embarked values with the most frequent category

Handled missing Sex values



2. Remove Duplicates

Ensured the dataset contains unique rows



3. Correct Data Types

Converted Fare and other numerical fields into correct numeric formats





---

Feature Engineering Steps

Extracted “Title” from passenger names
Example: Mr, Mrs, Miss, Master, etc.

Created Age Groups

Child (0–12)

Teen (13–18)

YoungAdult (19–35)

Adult (36–60)

Senior (60+)


Encoded Categorical Features

Sex → male:0, female:1

Embarked → S:0, C:1, Q:2


Dropped unnecessary columns such as Name



---

Sample Output (Processed Data)

PassengerId  Sex   Age  SibSp  Parch   Fare  Embarked  Title    AgeGroup
0            1    0  22.0      1      0   7.25         0     Mr  YoungAdult
1            2    1  38.0      1      0  71.28         1    Mrs       Adult
...


---

Generated File

processed_data.csv

This file contains:

Cleaned data

Numerical encodings

New engineered features

Ready-to-use ML dataset



---

Conclusion

This project demonstrates the essential steps of data cleaning and feature engineering, which significantly improve the quality and usability of any dataset. The resulting dataset is now suitable for machine learning models and further analysis.


---

Author

Sai Praneel
Department of Computer Science & Engineering

---
