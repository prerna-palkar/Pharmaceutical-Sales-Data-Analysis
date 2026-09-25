# 💊 Pharmaceutical Sales Data Analysis

## 📌 Project Overview

This project focuses on analyzing historical pharmaceutical sales data using **Python, Pandas, and Matplotlib**.

The goal is to explore daily sales patterns across different pharmaceutical drug categories, identify the highest-selling drugs, compare sales during specific periods, and understand monthly sales trends.

This project demonstrates fundamental **Data Analysis and Exploratory Data Analysis (EDA)** skills using real-world pharmaceutical sales data.

---

## 🎯 Objectives

The analysis answers the following questions:

1. What are the total sales quantities for each drug category (ATC code)?
2. Which drug categories have the highest total sales?
3. Which three drugs have the highest sales in:

   * January 2015
   * July 2016
   * September 2017
4. Which drug had the highest total sales in 2017?
5. Which drug category had the highest average daily sales?

---

## 📊 Dataset

The dataset contains daily pharmaceutical sales records along with information such as:

* Date
* Drug category / ATC codes
* Year
* Month
* Hour
* Weekday

The analysis uses the following drug categories:

* `M01AB`
* `M01AE`
* `N02BA`
* `N02BE`
* `N05B`
* `N05C`
* `R03`
* `R06`

### Dataset Source

The dataset was obtained from Kaggle:

[Pharma Sales Data](https://www.kaggle.com/milanzdravkovic/pharma-sales-data)

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas** — data loading, filtering, aggregation, and analysis
* **Matplotlib** — data visualization

google colab 

---

## 🔍 Analysis Performed

### 1. Total Sales by Drug Category

Calculated the total sales quantity for each ATC drug category using Pandas aggregation.

### 2. Highest-Selling Drug Categories

Compared total sales across drug categories and ranked them from highest to lowest.

### 3. Sales During Specific Periods

Filtered the dataset by year and month to identify the top three drugs for:

* January 2015
* July 2016
* September 2017

### 4. Sales in 2017

Filtered the dataset to 2017 and compared the total sales of all drug categories.

### 5. Average Daily Sales

Calculated the average daily sales for each drug category to determine which category had the highest average sales.

### 6. Monthly Respiratory Drug Sales

Analyzed `R03` sales by month to identify possible monthly or seasonal patterns.

---

## 📈 Data Analysis Techniques

The project uses several important Pandas operations:

```python
sum()
mean()
sort_values()
head()
groupby()
```

It also uses conditional filtering to analyze specific years and months.

Matplotlib was used to create charts for comparing sales across drug categories and time periods.

##

---

## 💡 Key Skills Demonstrated

* Data loading and exploration
* Data cleaning and preparation
* Pandas DataFrame operations
* Conditional filtering
* Grouping and aggregation
* Sorting and ranking
* Statistical analysis using mean and sum
* Data visualization
*

---

## 📌 Conclusion

This project demonstrates how Python and Pandas can be used to transform raw pharmaceutical sales data into meaningful information.

Through filtering, aggregation, statistical calculations, and visualization, the project identifies sales patterns across different drug categories and time periods.





