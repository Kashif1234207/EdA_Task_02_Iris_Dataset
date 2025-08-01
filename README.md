Exploratory Data Analysis (EDA) on Iris Dataset
This repository contains the complete EDA process performed on the classic Iris dataset as part of **Task 2** of the Data Science Internship at **High Tech Software House & Training Center**.

---

##  Dataset Overview

The Iris dataset consists of 150 rows and 5 columns:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species`

It includes measurements of iris flowers from three species: **Setosa**, **Versicolor**, and **Virginica**.


 Steps Performed in This Task

### 1. **Data Cleaning**
- Verified data types.
- Checked for missing values:  No missing values found.
- Checked for duplicates:  No duplicates found.
- One outlier was found in `sepal_width` using a boxplot and removed.

### 2. **Univariate Analysis**
- Plotted distribution of numerical features using histograms and boxplots.
- Calculated basic statistics: mean, median, mode, and standard deviation.

### 3. **Bivariate/Multivariate Analysis**
- Used scatter plots and pair plots to study relationships between variables.
- Correlation heatmap showed strong positive correlation between `petal_length` and `petal_width`.

### 4. **Data Visualization**
Used the following plots to visualize relationships and distributions:
-  **Bar plot** of species counts
-  **Box plot** of sepal length grouped by species
-  **Violin plot** of petal width grouped by species
-  **Joint plot** of sepal width vs petal width
-  **Pair plot** for all numerical features
-  **Heatmap** for feature correlation

---

##  Key Insights
- **Setosa** species is well-separated and easy to distinguish based on petal dimensions.
- **Petal length** and **petal width** are the most informative features for distinguishing species.
- One outlier was detected and removed in `sepal_width`.
- Strong positive correlation observed between petal features.
- Sepal features are less effective for class separation than petal features.

---

##  Tools and Libraries Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

##  Files in this Repository
- `Task_1_EDA.ipynb`: Jupyter notebook with full EDA process
- `README.md`: Summary of project steps and findings


## Author
*Kashif Nawaz*
_Data Science Intern_  
**High Tech Software House & Training Center*
 _This project is part of the internship curriculum and is for educational purposes._
