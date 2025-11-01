🧠 Pandas Student Performance Analysis
📋 Project Overview

This project analyzes student exam performance using Pandas, NumPy, and Matplotlib.
It demonstrates how data can be cleaned, transformed, analyzed, and visualized to extract key insights about student outcomes such as grades, pass/fail ratio, and preparation effectiveness.

🧹 Step 1–2: Data Cleaning & Preparation

Loaded dataset using Pandas

Checked for missing values and duplicates

Renamed inconsistent column names for clarity

Converted categorical columns (Gender, Ethnicity, etc.) to category type

⚙️ Step 3: Feature Engineering

Created new columns:

Total_Score → Sum of all subjects

Average_Score → Mean of scores per student

Result → Pass/Fail classification (based on average ≥ 33)

Grades → Assigned grade letters (A, B, C, D, E, F) using conditional logic

Used NumPy operations for efficient calculations

🔍 Step 4: Exploratory Data Analysis (EDA)

Average Score by Gender

Average Score by Ethnicity

Effect of Test Preparation on performance

Correlation analysis between numerical features

📊 Step 5: Visualization Dashboard

Created an interactive data visualization dashboard using Matplotlib and Seaborn:

Visualization	Purpose
Histogram	Distribution of average scores
Barplots	Comparison by Gender, Ethnicity, and Test Prep
Boxplot	Spread of scores by Gender
Heatmap	Correlation between numerical variables
Countplot	Pass/Fail distribution

📈 Insight Highlights:

Students who completed Test Preparation scored significantly higher.

Female students slightly outperformed males on average.

Group E ethnicity performed best overall.

Strong positive correlation between Math, Reading, and Writing scores.
