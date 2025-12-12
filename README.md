🏥 Healthcare Patient Analysis – EDA Project

📌 Project Summary

This project focuses on analyzing a comprehensive healthcare patient dataset containing 6,000+ medical records, with the goal of understanding patient demographics, disease patterns, and critical health indicators. Using Python libraries including Pandas, NumPy, Matplotlib, and Seaborn, the analysis explores how medical factors such as Blood Sugar, Cholesterol, Heart Rate, Smoking Status, Gender, and Disease Type impact patient outcomes.

Through visualizations such as boxplots, heatmaps, scatter plots, pairplots, histograms, bar charts, and pivot-based heatmaps, the project uncovers insights like older individuals having higher blood sugar levels, smokers showing a higher likelihood of being under treatment, and certain cities showing higher prevalence of diseases. The study provides a thorough understanding of health trends and risk indicators that can support data-driven decision-making in hospitals and clinics.

🚀 Project Objective

1️⃣ Analyze how key medical indicators (Blood Sugar, Cholesterol, Heart Rate) vary across demographic groups such as Age, Gender, City, and Smoker Status.

2️⃣ Identify which diseases are most commonly reported and analyze their distribution across different cities and patient groups.

3️⃣ Examine trends in health risks such as high blood pressure, diabetes indicators, obesity, and their relationship with age and lifestyle factors.

4️⃣ Perform categorical vs numerical analysis to understand how medical metrics differ based on Outcome (Recovered / Under Treatment).

5️⃣ Conduct bivariate and multivariate analysis using boxplots, heatmaps, scatterplots, pairplots, correlation matrices, and pivot table heatmaps to uncover relationships across 10+ dataset features.

📊 Tools & Technologies Used

Python 3

Pandas – data cleaning, processing, and wrangling

NumPy – numerical operations

Matplotlib – for static plots

Seaborn – for advanced statistical and multivariate visualizations

Jupyter Notebook – used for development and step-by-step EDA

Excel / CSV Dataset – primary data source

🔍 Analysis Performed
🔹 Univariate Analysis

Distribution of Age, Blood Sugar, Cholesterol, Heart Rate

Countplots for Gender, City, Diseases, and Smoker Status

🔹 Bivariate Analysis

Boxplots (Blood Sugar vs Gender, Cholesterol vs Smoker)

Scatterplots (Heart Rate vs Blood Sugar, Age vs Cholesterol)

Barplots (Average Blood Sugar by City, Cholesterol by Outcome)

🔹 Multivariate Analysis

Correlation Heatmap

Pairplot of numerical features

Pivot Table Heatmap (City × Disease × Blood Sugar)

Scatterplot with hue (Age vs Blood Sugar by Smoker Status)

Boxplot with hue (Cholesterol by Gender & Smoker)

✨ Key Insights

Blood Sugar and Cholesterol levels increase with Age, indicating higher risks for older patients.

Smokers have a higher proportion of “Under Treatment” outcomes, emphasizing lifestyle impact.

Certain cities show higher disease prevalence, suggesting region-based risk factors.

Weight and Cholesterol are strongly correlated, indicating obesity-related risks.

Middle-age groups (30–50 years) show the highest number of cases for major diseases such as hypertension and heart ailments.

Heart Rate is generally lower for older individuals, aligning with medical trends.

🚀 Feature Enhancements (Future Scope)

Build predictive ML models (Logistic Regression, Random Forest) for Disease Prediction.

Add clustering models (K-Means) for Patient Risk Segmentation.

Create a Power BI / Tableau Dashboard for interactive healthcare analytics.

Develop a health risk scoring system using combined medical indicators.

Automate EDA steps using a Python script for real-time health analysis.

Add anomaly detection for sudden spikes in Blood Sugar / Heart Rate.
