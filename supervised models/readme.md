📈 Linear Regression Model — Advertising Dataset Analysis

This project implements a Linear Regression Model to analyze how advertising expenditures across different media channels (TV, Radio, Newspaper) affect product sales.
The notebook includes complete data exploration, visualization, and preparation for predictive modeling.

🧠 Project Overview

The analysis aims to understand which advertising channel contributes the most to sales performance.
It follows a structured data science workflow:

✅ Data Loading & Cleaning

✅ Data Quality Assessment

✅ Exploratory Data Analysis (EDA)

✅ Correlation & Visualization

✅ Model Preparation for Linear Regression

📊 Dataset

File: Advertising.csv
Records: 200 observations

Feature	Description
TV	Advertising budget on TV (in thousands of dollars)
Radio	Advertising budget on Radio (in thousands of dollars)
Newspaper	Advertising budget on Newspaper (in thousands of dollars)
Sales	Product sales (in thousands of units)
🔍 Key Steps Performed
1️⃣ Data Loading & Initial Exploration

Imported data using pandas

Removed unnecessary Unnamed: 0 column

Verified absence of missing values and duplicates

Reviewed descriptive statistics and data types

2️⃣ Data Quality Assessment
Check	Result
Missing Values	None
Duplicates	None
Data Types	All numerical (float64)
3️⃣ Exploratory Data Analysis (EDA)

Calculated key descriptive statistics

Generated a correlation matrix and heatmap

Insights:

📺 TV advertising shows the strongest correlation with sales

📻 Radio has a moderate correlation

🗞️ Newspaper has a weak correlation

4️⃣ Data Visualization

Correlation Heatmap (Seaborn)

Interactive Scatter Plots (Plotly):

Radio vs Newspaper (colored by Sales)

Radio vs Sales

Sales vs TV

These visualizations help identify trends and relationships in the data.

⚙️ Technical Setup
📚 Libraries Used

numpy → Numerical computations

pandas → Data manipulation

matplotlib → Static visualizations

seaborn → Statistical data visualization

plotly → Interactive charts

scikit-learn → ML tools (MinMaxScaler, train_test_split)

🧩 Installation
pip install pandas numpy matplotlib seaborn plotly scikit-learn

🚀 Next Steps

This notebook prepares the dataset for Linear Regression modeling by:

Exploring and cleaning the data

Identifying key relationships

Highlighting which advertising channel most strongly impacts sales

Findings:

💡 TV advertising has the highest influence on sales, followed by radio. Newspaper advertising shows minimal impact.

🧰 Usage

Open the Jupyter Notebook or Google Colab.

Run all cells sequentially.

View interactive visualizations (supported in Jupyter and Colab).

🧾 Summary

This project provides a solid foundation for:

Understanding Linear Regression concepts

Performing Exploratory Data Analysis

Building predictive models for marketing optimization
