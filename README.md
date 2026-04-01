#  Retail Sales Data Analysis (Pandas & NumPy)

##  Overview

This project performs data analysis on a retail sales dataset using Python libraries like Pandas and NumPy. It includes data cleaning, transformation, and extraction of meaningful business insights such as revenue trends and category performance.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

---

##  Dataset

The dataset contains retail transaction details such as:

* Date
* Product Category
* Region
* Quantity
* Price

---

##  Steps Performed

### 1. Data Loading

* Loaded dataset into a Pandas DataFrame
* Displayed structure and preview

### 2. Data Cleaning

* Identified missing values
* Replaced missing values in Quantity & Price with mean
* Removed rows with missing Category or Region

### 3. Feature Engineering

* Created a new column **Revenue = Quantity × Price**

### 4. Data Analysis

* Calculated total revenue
* Grouped data by Product Category and Region
* Identified top and bottom performing categories
* Found highest and lowest revenue regions

### 5. Time-Based Analysis

* Converted Date column to datetime format
* Extracted month from Date
* Calculated monthly revenue trends

### 6. Statistical Analysis

* Computed mean, median, and standard deviation of revenue

---

##  Key Insights

* Revenue distribution across categories and regions
* Top-performing and underperforming product categories
* Monthly revenue trends for business insights

---

##  How to Run

1. Install required libraries:

   ```
   pip install pandas numpy
   ```
2. Open Jupyter Notebook
3. Place dataset file in the same directory
4. Run cells sequentially

---

##  Output

* Cleaned dataset
* Revenue calculations
* Category & region analysis
* Monthly revenue trends
* Statistical summary


