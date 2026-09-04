# Superstore Sales Performance Analysis and Customer Insights

## 1. Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a Superstore sales dataset to uncover meaningful business insights related to sales performance, profitability, customer segments, product categories, discounts, and regional trends. The analysis helps identify patterns, correlations, and opportunities for improving business decisions through data-driven insights.
The project includes data cleaning, statistical analysis, visualization, and insight generation using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

---

## 2. Tools & Technologies Used
* **Python** - Programming language used for analysis
* **Pandas** - Data loading, cleaning, manipulation, and aggregation
* **Matplotlib** - Data visualization and plotting
* **Seaborn** - Statistical data visualization
* **Plotly** - Interactive visualizations
* **Google Colab** - Development environment for analysis and reporting

---

## 3. Dataset Information
* **Source:** Downloaded from public.tableau
* **Description:** Structured sales information with key fields including Order ID, Order Date, Ship Date, Ship Mode, Customer Info, Region, Category, Sub-Category, Sales, Quantity, Discount, and Profit.

---

## 4. Steps Followed
1. **Data Collection:** Loaded the Superstore sales dataset into Google Colab using Pandas.
2. **Data Understanding:** Explored structure using `head()`, `tail()`, `info()`, and `describe()`.
3. **Data Cleaning:** Handled missing values, duplicates, and incorrect data types.
4. **Feature Engineering:** Derived key parameters such as `Total_Sales`, `Total_Profit`, `Profit_Margin`, `Discount_Amount`, `Month`, and `Year`.
5. **Exploratory Data Analysis (EDA):** Performed univariate, bivariate, and multivariate analysis alongside GroupBy operations and pivot tables.
6. **Data Visualization:** Generated charts to evaluate trends, profitability, customer segments, and discount impacts.

---

## 5. Key Insights
* **Top Category:** The Technology category generated the highest sales and profit.
* **Top Region:** The West region showed the strongest overall sales performance.
* **Discount Impact:** High discounts negatively affected profitability; profit margin decreased significantly with higher discount rates.
* **Customer Segments:** The Consumer segment contributed to the highest number of sales.
* **Shipping Mode:** Standard Class was the most frequently used shipping mode.
* **Seasonality:** Sales exhibited clear seasonal trends across different months.

---

## 6. Visualizations Included
* **Bar Plot:** Compare sales across categories.
* **Line Chart:** Analyze monthly sales trends.
* **Pie Chart:** Segment-wise sales contribution.
* **Histogram:** Distribution of sales data.
* **Box Plot:** Detect outliers in profit and sales.
* **Scatter Plot:** Relationship between sales and profit.
* **Heatmap:** Correlation matrix of numerical variables.
* **Count Plot:** Shipping mode frequencies.
* **Interactive Plotly Charts:** Regional and category breakdowns.

---

## 7. Project Repository Structure
* `superstore_data.xls` - Raw dataset
* `superstore_sales_main_project.ipynb` - Pandas analysis and visualizations notebook
* `README.md` - Project documentation and summary

---

## 8. How to Run the Project
1. Open Google Colab or Jupyter Notebook.
2. Clone or download this repository.
3. Open `superstore_sales_main_project.ipynb`.
4. Run all cells sequentially to view data cleaning, analysis, and interactive plots.

---

## 9. Conclusion
This project demonstrates how Python libraries can be leveraged for real-world sales analysis. The insights gained can guide businesses in understanding customer behavior, optimizing sales strategies, and driving profitability.
