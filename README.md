# student-performance-analysis
## Project Title: Student Performance Analysis using Python (Pandas, Seaborn, Matplotlib)
## Overview
In this project, I explored the **Students Performance Dataset** using **Python**, applying core data analysis techniques to uncover patterns and insights about what influences student academic outcomes.
The dataset contained 1,000 student records with information such as **gender, parental education, lunch type, test preparation course**, and **scores in math, reading, and writing**.
## Tools & Libraries
* **Python**
* **Pandas** — I used Pandas for data cleaning, manipulation, and aggregation
* **Seaborn** and **Matplotlib** — These were used for data visualization
* **Jupyter Notebook** — for interactive analysis
## Key Steps
1. **Data Loading & Cleaning**
   * I imported the dataset and verified there were no missing values.
   * I renamed columns for easier access and consistency.
2. **Feature Engineering**
   * I created a new column, `average`, representing each student’s mean score across math, reading, and writing.
3. **Exploratory Data Analysis (EDA)**
   * I generated summary statistics with `df.describe()`.
   * I analyzed relationships between performance and demographic factors such as **gender** and **test preparation**.
   * I visualized distributions using histograms, boxplots, and correlation heatmaps.
4. **Categorical Encoding**
   * I converted text-based features (like gender) into numeric values to enable statistical analysis and correlation computation.
## Key Insights
* **Average Student Performance:**
  * Math: 66.09 | Reading: 69.17 | Writing: 68.05
* **Gender Analysis:**
  * Female students outperformed male students on average
    * Female average: **69.6**
    * Male average: **65.8**
* **Test Preparation Course Impact:**
  * Students who **completed** the test prep course scored significantly higher
    * Completed: **72.7**
    * None: **65.0**
* **Subject Correlation:**
  * Strong positive correlations between math, reading, and writing (r ≈ 0.8–0.97).
  * Suggests students who perform well in one subject tend to perform well in others.
## Visualizations Created
* Distribution of overall average scores (Using `sns.histplot`)
* Gender-wise comparison of math scores (Using `sns.boxplot`)
* Correlation heatmap of numerical variables (Using `sns.heatmap`)
## Conclusion
This analysis highlights how **test preparation and consistent study habits** can significantly improve student performance.
It also shows how exploratory data analysis (EDA) can uncover patterns and guide actionable decisions in education data.
## Project Files
 *Dataset Source:* [Kaggle – Students Performance in Exams Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
