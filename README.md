# Python-Automation-Data-Cleaning-App
The Data Cleaning App is a Python-based automation tool designed to clean datasets efficiently. This app performs data cleaning tasks such and saving the cleaned data for further use. Additionally, it saves a copy of the duplicate records for reference and ensures proper data hygiene for analysis or processing.

# Data Cleaning App

## Overview
The **Data Cleaning App** is a Python-based automation tool designed to clean datasets efficiently.  
This app performs essential data cleaning tasks such as:  
- Removing duplicates
- Handling missing values
- Saving cleaned data for further use  
Additionally, it saves a copy of duplicate records for reference, ensuring proper data hygiene for analysis or processing.

---

## Functionality Description

### **Input**
- Takes the dataset path and file name as input from the user.

### **Duplicate Handling**
- Identifies duplicates in the dataset using `pandas.DataFrame.duplicated()`.
- Stores duplicate rows in a file named `duplicates.csv`.
- Removes duplicates from the original dataset.

### **Missing Value Handling**
- **Numeric Columns**: Replaces missing values with the column mean using `pandas.DataFrame.mean()`.
- **Non-Numeric Columns**: Drops rows with missing values using `pandas.DataFrame.dropna()`.

### **Saving the Data**
- Saves the cleaned dataset to a file named `cleaned_data.csv`.

### **Outputs**
- **cleaned_data.csv**: Contains the cleaned dataset without duplicates or missing values.
- **duplicates.csv**: Contains all duplicate records for reference.

---

## Sample Output

### **Cleaned Data (`cleaned_data.csv`)**
- A cleaned dataset with all duplicates removed and missing values handled appropriately.

### **Duplicate Records (`duplicates.csv`)**
- All duplicate rows from the original dataset saved for reference.



