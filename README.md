<div align="center">

# 📊 Company Size & Salary Analysis 📊

*An in-depth analysis of salary trends across different company sizes and career levels.*

</div>

---

## 📌 Project Overview

> This project explores the relationship between **company size** and **employee salary** using a dataset (`test.csv`). The goal is to understand salary trends across different company sizes and career levels, while also applying data cleaning, transformation, and visualization techniques.

---

## 🛠️ Tools & Libraries

| Tool / Library      | Icon | Purpose                                    |
| :------------------ | :--: | :----------------------------------------- |
| **Python** |  🐍  | Core language for data analysis.           |
| **Pandas** |  🐼  | Data manipulation, cleaning, and analysis. |
| **Matplotlib & Seaborn** |  📊  | Data visualization and plotting.           |
| **NumPy** |  🔢  | Numerical operations and array handling.   |

---

## 🔎 Key Steps

1.  **Data Import & Cleaning**
    -   Loaded dataset with `pandas`.
    -   Standardized `company_size` column (handled missing/unknown values).
    -   Converted company size into **ordered categories**.

2.  **Exploratory Data Analysis (EDA)**
    -   Checked unique values and data distributions.
    -   Grouped salaries by company size and career level.
    -   Calculated **mean** and **median** salaries.

3.  **Visualization**
    -   📈 **Bar Plot**: Average salary across company sizes.
    -   📦 **Box Plot**: Salary distribution (with outlier handling).
    -   📊 **Log Transformation**: To better visualize skewed salary data.

---

## 📊 Insights

-   Smaller companies (1–50 employees) show wider salary variation and more outliers.
-   Larger companies tend to have **higher average salaries**, but with less variation.
-   Career level plays a significant role in salary differences, regardless of company size.

---

## 🚀 Future Work

-   [ ] Expand analysis with additional features (e.g., industry, location).
-   [ ] Build predictive models to estimate salary based on company size and career level.
-   [ ] Deploy interactive dashboards for dynamic insights.

---

## ▶️ How to Use

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Install Dependencies**
    Make sure you have **Python 3.x** installed. Then, install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

3.  **Add the Dataset**
    Place the dataset file **`test.csv`** into the root directory of the project.

4.  **Run the Analysis**
    Open the Jupyter Notebook or Python script in your preferred IDE. Here is a sample snippet to get started:
    ```python
    import pandas as pd

    # Load the dataset with the correct separator
    df = pd.read_csv('test.csv', sep='|')

    # Display the first 5 rows to verify
    print(df.head())
    ```

5.  **Explore the Results**
    Run the cells or sections of the script to reproduce the analysis and visualizations.

---
