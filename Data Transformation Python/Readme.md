
#  Data Transformation & Preprocessing Project (Python)

##  Project Overview
This project focuses on preparing a dataset for Machine Learning by applying essential data preprocessing techniques such as encoding, normalization, standardization, and building a preprocessing pipeline.

The goal is to convert raw data into a clean and structured format suitable for machine learning models.

---

## Dataset
- File: `employee_productivity_dataset.csv`
- Contains employee-related information such as:
  - Age
  - Salary
  - Hours Worked Per Week
  - Performance Score
  - Department
  - Work Mode
  - Location

---

##  Objectives
- Handle missing values using appropriate techniques  
- Convert categorical data into numerical form  
- Apply One-Hot Encoding  
- Normalize numerical features  
- Standardize data  
- Compare scaling methods  
- Build and apply a preprocessing pipeline  
- Prepare dataset for machine learning  

---

##  Technologies Used
- Python   
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

##  Steps Performed

### 1. Missing Value Handling
- Age → Median  
- Salary → Mean  
- Hours Worked → Median  
- Performance Score → Mean  

### 2. Label Encoding
- Converted Gender and Department into numeric values  

### 3. One-Hot Encoding
- Applied on Work_Mode and Location  

### 4. Normalization (Min-Max Scaling)
- Scaled Salary and Hours_Worked_Per_Week between 0 and 1  

### 5. Standardization
- Applied StandardScaler on Age and Projects_Completed  

### 6. Scaling Comparison
- Compared MinMaxScaler and StandardScaler on Salary  

### 7. Preprocessing Pipeline
- Used ColumnTransformer and Pipeline  
- Applied encoding and scaling together  

### 8. Pipeline Application
- Transformed dataset into machine learning-ready format  

---

## Visualizations
- Distribution plots after handling missing values  
- Bar chart for encoded categorical variables  
- Scaling comparison graphs  
- Normalization and standardization visualizations  

---

##  Files in Repository
- `Data Transformation Python.ipynb` → Main notebook  
- `employee_productivity_dataset.csv` → Dataset  
- `Question Paper.pdf` → Assignment questions  
- `README.md` → Project documentation  

---

##  Conclusion
Data transformation techniques such as encoding, normalization, and scaling are essential for preparing datasets for machine learning. These steps improve data consistency, reduce bias, and enhance model performance.

---

##  Author
**Abhilasha Pareek**

---

##  Acknowledgement
This project is part of a Data Transformation assignment for academic learning purposes.
