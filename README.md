# 📌 Project Overview

This project demonstrates Python fundamentals and data analytics skills using NumPy and Pandas.
It simulates a real-world business scenario involving employees, projects, costs, and performance evaluation, and applies data cleaning, transformation, and analysis techniques to derive meaningful insights.

### 🛠️ Tools & Technologies Used:<br>
• Python<br>
• NumPy<br>
• Pandas<br>
• CSV file handling<br>
• Jupyter Notebook<br> 

### 📂 Dataset Description

Three datasets were created and stored as CSV files:

1.) Project.csv <br>
Project details such as Project Name, Cost, Status

2.) Employee.csv <br>
Employee demographic details

3.) Seniority_Level.csv<br>
Employee designation levels

## 🧩 Tasks Performed<br>
✅ Task 1: Data Creation & Storage<br>
• Created three DataFrames using Python dictionaries<br>
• Converted them into Pandas DataFrames<br>
• Saved them as CSV files for reuse<br>

✅ Task 2: Handling Missing Values<br>
• Identified missing values in the Cost column<br>
• Implemented a custom running-average algorithm using a for loop<br>
• Replaced missing values without using built-in mean functions

✅ Task 3: Column Transformation<br>
• Split the Name column into: First Name and Last Name<br>
• Removed the original Name column<br>
• Reorganized columns for better readability

✅ Task 4: Data Merging<br>
• Joined all three datasets using ID<br>
• Created a unified DataFrame called Final <br>
• Used inner join logic to maintain data integrity

✅ Task 5: Business Rule – Bonus Calculation<br>
• Added a new column Bonus<br>
• Applied 5% bonus on project cost<br>
• Bonus granted only if project status is "Finished"<br>

✅ Task 6: Designation Update & Data Cleaning<br>
• Demoted employees whose project status was "Failed"<br>
• Removed records where designation level exceeded 4<br>

✅ Task 7: String Manipulation<br>
• Added prefixes: "Mr." for male employees and "Mrs." for female employees<br>
• Dropped the Gender column after transformation<br>

✅ Task 8: Conditional Promotion Logic<br>
• Promoted employees whose age > 29<br>
• Implemented logic using an if condition inside a loop

✅ Task 9: Aggregation & Analysis<br>
• Calculated total project cost per employee<br>
• Created a new DataFrame TotalProjCost with:ID ,First Name ,Total Cost

✅ Task 10: Filtering & Pattern Matching<br>
• Filtered employee records where City contains the letter "O"


## 📈 Skills Demonstrated<br>
• Data Cleaning & Preprocessing<br>
• Data Wrangling with Pandas <br>
• Conditional Logic & Loops <br>
• CSV File Handling<br>
• Business Rule Implementation<br>
• Exploratory Data Analysis 
