**This project demonstrates data analysis using Python libraries Pandas and NumPy on a retail sales dataset. The objective is to perform data cleaning,
handle missing values, calculate revenue, and generate business insights through data aggregation and statistical analysis.**

**Technologies Used**
Python
Pandas
NumPy
Google Colab / VS Code
Dataset

**The dataset contains retail transaction information such as:**
Date
Product Category
Quantity
Price
Region

**Tasks Performed**
Q1. **Load Dataset**
Loaded the retail dataset into a Pandas DataFrame.
Displayed the first 5 rows and dataset information.

Q2. **Missing Value Analysis**
Identified missing values in each column.
Calculated the total number of missing values.

Q3. **Data Cleaning**
Replaced missing values in:
Quantity column using mean
Price column using mean

Q4. **Remove Incomplete Records**
Removed rows where:
Product Category is missing
Region is missing

Q5. **Revenue Calculation**
Created a new column: Revenue = Quantity × Price

Q6. **Total Revenue Analysis**
Calculated total revenue generated from all transactions.

Q7. **Category-wise Revenue**
Grouped data by Product Category.
Calculated total revenue for each category.

Q8.** Revenue Ranking**
Identified:
Top 3 Product Categories
Bottom 3 Product Categories

Q9. **Regional Revenue Analysis**
Grouped data by Region.
Identified:
Highest Revenue Region
Lowest Revenue Region

Q10. **Statistical Analysis**

Calculated:
Mean Revenue
Median Revenue
Standard Deviation of Revenue

**Project Structure**
Retail-Sales-Analysis/
│
├── retail_dataset.csv
├── retail_analysis.ipynb
├── README.md
How to Run
Google Colab
Open Google Colab.
Upload retail_dataset.csv.
Run all notebook cells.
VS Code

**Install required libraries:**

**pip install pandas numpy**

Run:
python retail_analysis.py
Key Learning Outcomes
Data Loading using Pandas
Data Cleaning Techniques
Handling Missing Values
NumPy Operations
GroupBy Analysis
Revenue Calculations
Descriptive Statistics
Data Aggregation and Reporting
Author

Utkarsh Rai
Data Analytics with Generative AI | PW Skills
