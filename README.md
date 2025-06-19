# Diwali Sales Analysis


## 📖 Introduction

This project provides an in-depth Exploratory Data Analysis (EDA) of a Diwali sales dataset. The primary goal is to uncover trends and patterns in customer purchasing behavior to derive actionable business insights. By cleaning, processing, and visualizing the data, this analysis identifies key demographics, popular product categories, and high-revenue regions.

---

## 🎯 Project Objective

The main objectives of this analysis were to answer the following key business questions:

*   **Customer Profiling:** Who are the most valuable customer segments by age, gender, marital status, and occupation?
*   **Geographic Performance:** Which states contribute the most to sales?
*   **Product Strategy:** What are the top-selling product categories?
*   **Actionable Insights:** How can these findings be used to improve sales, target marketing efforts, and manage inventory more effectively?

---

## 📊 Dataset

The dataset used for this analysis is a CSV file containing 11,251 rows of fictional sales data. It includes customer information and purchase details.

**Key columns analyzed:**
*   `User_ID`
*   `Gender`
*   `Age Group`
*   `Marital_Status`
*   `State`
*   `Occupation`
*   `Product_Category`
*   `Orders`
*   `Amount`

---

## 🛠️ Tech Stack & Libraries Used

*   **Python:** The core programming language used for the analysis.
*   **Pandas:** For data manipulation, cleaning, and wrangling.
*   **NumPy:** For numerical operations and computations.
*   **Matplotlib:** For creating basic static visualizations.
*   **Seaborn:** For generating more advanced and aesthetically pleasing statistical plots.
*   **Jupyter Notebook:** As the interactive environment for writing and presenting the code.

---

## ⚙️ Analysis Workflow

The project followed a structured data analysis workflow:

1.  **Data Sourcing:** Imported the dataset from the CSV file.
2.  **Data Cleaning:**
    *   Handled null values by dropping unnecessary columns and empty rows.
    *   Corrected data types for relevant columns (e.g., `Amount`).
    *   Renamed columns for better readability and consistency.
3.  **Exploratory Data Analysis (EDA):**
    *   Performed statistical analysis using the `describe()` method to get a high-level overview.
    *   Analyzed data by grouping it based on Gender, Age Group, State, Marital Status, and Occupation.
4.  **Data Visualization:**
    *   Created various charts and plots to visualize the findings and make them easy to interpret.

---

## ✨ Key Insights & Findings

The analysis revealed several key insights:

*   **Gender:** Married women aged 26-35 from states like UP, Maharashtra, and Karnataka are the primary contributors to sales, especially in the IT, Healthcare, and Aviation sectors.
*   **Top States:** The top 3 states by sales are Uttar Pradesh, Maharashtra, and Karnataka.
*   **Top Product Categories:** The most popular product categories are Food, Clothing & Apparel, and Electronics & Gadgets.
*   **Marital Status:** Married individuals have a significantly higher purchasing power compared to unmarried individuals.

---

## 📈 Visualizations

Below are some of the visualizations created to represent the findings.

> **Note:** To see the full interactive analysis and all plots, please open the `Diwali_Sales_Analysis.ipynb` file.

**Sales by Gender**
*A bar chart showing that females have higher purchasing power than males.*
![Sales by Gender](https://via.placeholder.com/600x400.png?text=Chart:+Sales+by+Gender)

**Sales by Age Group**
*A grouped bar chart showing the 26-35 age group has the highest sales, with females leading in every group.*
![Sales by Age Group](https://via.placeholder.com/600x400.png?text=Chart:+Sales+by+Age+Group)

**Top 10 States by Orders**
*A bar chart highlighting the top 10 states with the highest number of orders.*
![Top 10 States](https://via.placeholder.com/600x400.png?text=Chart:+Top+10+States+by+Orders)

**Top Selling Product Categories**
*A bar chart illustrating the most popular product categories by sales amount.*
![Top Product Categories](https://via.placeholder.com/600x400.png?text=Chart:+Top+Product+Categories)

---

## 🚀 How to Run this Project

To replicate this analysis on your own machine, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/diwali-sales-analysis.git
    cd diwali-sales-analysis
    ```
2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```
3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  Open the `Diwali_Sales_Analysis.ipynb` file and run the cells.

---

## 🏁 Conclusion

This analysis successfully identified key trends in the Diwali sales data. The insights derived can empower the business to make data-driven decisions, such as tailoring marketing campaigns to specific demographics and optimizing inventory based on top-performing product categories and regions.
