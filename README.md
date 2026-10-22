# Exploratory Data Analysis (EDA) – Students Performance

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a Students Performance dataset using Python. It analyzes students' mathematics, reading, and writing scores to understand their performance and calculate useful statistics.

## Objectives
- Explore and understand the dataset.
- Check the dataset structure and missing values.
- Calculate statistical measures such as mean, median, mode, and standard deviation.
- Calculate total score, percentage, and average score for each student.
- Classify students as Pass or Fail based on their scores.
- Identify outliers and visualize score distributions.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Dataset
The project uses the `StudentsPerformance.csv` dataset, which contains information about students and their academic scores.

The analysis focuses on these columns:
- `math score`
- `reading score`
- `writing score`

Other dataset columns are retained for exploring student information.

## Tasks Performed

### 1. Data Exploration
- Displayed the dataset.
- Checked the first and last rows.
- Examined the number of rows and columns.
- Checked column data types and dataset information.

### 2. Statistical Analysis
Calculated:
- Mean
- Median
- Mode
- Standard deviation
- First quartile (25th percentile)
- Descriptive statistics

### 3. Feature Engineering
Created the following new columns:

- **Total Score:** Sum of mathematics, reading, and writing scores.
- **Percentage:** Total score divided by 300 and multiplied by 100.
- **Average Score:** Average of the three subject scores.
- **Pass/Fail:** Students are classified as Pass if they score at least 40 in all three subjects; otherwise, they are classified as Fail.

### 4. Outlier Detection
Used the Interquartile Range (IQR) method to calculate the lower and upper limits and identify outliers in mathematics scores.

### 5. Data Visualization
Created visualizations to understand the score distribution:
- Histogram of mathematics scores.
- Box plot comparing mathematics, reading, and writing scores.

## How to Run the Project
1. Download the notebook and the `StudentsPerformance.csv` dataset.
2. Open `EDA_7.ipynb` in Jupyter Notebook or Google Colab.
3. Upload the CSV dataset to the environment.
4. Update the file path if necessary.
5. Run the cells in order.

## Conclusion
This project demonstrates how Python libraries can be used to explore student data, calculate academic performance metrics, identify mathematics score outliers, and visualize score distributions. It provides a basic understanding of data analysis using EDA techniques.

## Author
Sangeetha
