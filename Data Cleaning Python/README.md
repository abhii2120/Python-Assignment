#  Healthcare Data Cleaning Project (Python)

##  Project Overview
This project focuses on cleaning and preprocessing a healthcare dataset using Python. The goal is to improve data quality by handling missing values, removing duplicates, treating outliers, and applying transformations for better analysis.

---

##  Dataset
- File: `healthcare_data_cleaning_dataset.csv`
- The dataset contains patient-related information such as:
  - Age
  - Treatment Cost
  - Admission Date
  - Other healthcare attributes

---

##  Objectives
The main objectives of this project are:
- Identify and handle missing values
- Replace missing data using appropriate techniques (Mean/Median)
- Detect and remove duplicate records
- Identify and handle invalid data
- Detect outliers using IQR method
- Treat outliers using Winsorization
- Apply log transformation to reduce skewness
- Handle time-based missing values
- Visualize data for better understanding

---

##  Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib

---

##  Data Cleaning Steps

### 1. Missing Data Identification
- Identified missing values in each column
- Calculated percentage of missing data

### 2. Handling Missing Age
- Replaced missing values using **median**
- Reason: Robust against outliers

### 3. Handling Missing Treatment Cost
- Used **median imputation**
- Reason: Data is highly skewed

### 4. Duplicate Records
- Identified duplicate rows
- Removed duplicates to improve accuracy

### 5. Invalid Age Values
- Removed unrealistic values (<0 and >100)

### 6. Outlier Detection
- Used **IQR method**
- Detected extreme values

### 7. Outlier Treatment
- Applied **Winsorization (5th & 95th percentile)**
- Retained all records

### 8. Log Transformation
- Reduced skewness in Treatment Cost
- Created new column: `Log_Treatment_Cost`

### 9. Time-Based Handling
- Sorted data by `Admission_Date`
- Applied forward fill method

---

## Visualizations
The following visualizations were used:
- Bar chart for missing values
- Histogram for Age and Treatment Cost
- Boxplot for outlier detection
- Before vs After transformation plots
- Line chart for time-based trends

---

##  Files in Repository
- `Data_cleaning_Python.ipynb` → Main notebook
- `healthcare_data_cleaning_dataset.csv` → Dataset
- `Question Paper.pdf` → Assignment questions
- `Data cleaning Python.ipynb pdf.pdf` → Final PDF report
- `README.md` → Project documentation

---

##  Conclusion
Data cleaning techniques significantly improved the quality, consistency, and reliability of the dataset. The cleaned data is now ready for further analysis and decision-making.

---

##  Author
**Abhilasha Pareek**

---

##  Acknowledgement
This project is part of a Data Cleaning assignment for learning and academic purposes.
