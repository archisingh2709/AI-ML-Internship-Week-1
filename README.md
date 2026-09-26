# Week 1 — Python & Data Analysis Fundamentals

## AI & ML Internship Practical Assignment

### Project Title
**Student Performance Data Analysis using Python**

## 1. Project Objective
The objective of this practical is to gain hands-on experience with Python and basic data analysis using Pandas, NumPy and Matplotlib.

## 2. Dataset
The project uses a sample **Student Performance Dataset** containing information about:
- Student ID
- Name
- Gender
- Age
- Study Hours
- Attendance
- Math Score
- Science Score
- English Score

The CSV intentionally contains a small number of missing values and one duplicate record so that data-cleaning operations can be demonstrated.

## 3. Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

## 4. Tasks Completed
1. Loaded the CSV dataset using Pandas.
2. Identified the number of rows and columns.
3. Analyzed the dataset structure and data types.
4. Checked for missing values.
5. Identified duplicate records.
6. Performed basic data cleaning.
7. Generated statistical insights.
8. Created more than 3 visualizations using Matplotlib.

## 5. Visualizations
The notebook contains:
1. Average Math Score by Gender — Bar Chart
2. Distribution of Study Hours — Histogram
3. Study Hours vs Math Score — Scatter Plot
4. Average Score by Subject — Bar Chart

## 6. Data Cleaning
Missing numeric values are replaced using the median of the corresponding column. Duplicate records are removed and the index is reset.

## 7. How to Run

### Option A — Jupyter Notebook
1. Install Python.
2. Install required libraries:
   `pip install pandas numpy matplotlib jupyter`
3. Open a terminal in this project folder.
4. Run:
   `jupyter notebook`
5. Open `Week_1_Python_Data_Analysis.ipynb`.
6. Run all cells from top to bottom.

### Option B — VS Code
1. Open the project folder in VS Code.
2. Install the Python and Jupyter extensions.
3. Open the `.ipynb` file.
4. Select a Python 3 kernel.
5. Run the cells one by one or choose **Run All**.

## 8. Expected Output
The notebook will display:
- Dataset preview
- Dataset dimensions
- Data types
- Missing-value report
- Duplicate-record report
- Statistical summary
- Average scores
- Four charts
- A cleaned CSV file

## 9. Conclusion
This project demonstrates the basic data-analysis workflow:

**Load → Inspect → Clean → Analyze → Visualize → Save**

It provides practical experience with the fundamentals required for further Machine Learning work.
