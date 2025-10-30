# GDG Task 1 — Exploratory Data Analysis (EDA) on Crab Dataset
Welcome to the GDG Task 1 repository! This project walks through the essential steps of Exploratory Data Analysis (EDA) using a real-world crab dataset.

Dataset
The dataset comprises 74,051 rows and 9 key columns, measuring various crab morphometrics:

Sex: Crab gender (M, F, I)

Length, Diameter, Height, Weight, Shucked Weight, Viscera Weight, Shell Weight: Various physical and anatomical measurements

Age: Estimated age of each crab

This notebook covers:

Basic EDA Concepts: Overview and explanation

Data Loading & Inspection: Reading, previewing, and inspecting missing values and column types

Descriptive Statistics: Count, mean, standard deviation, percentiles, five-number summary

Data Cleaning: Removing rows with nonsensical values (e.g., height = 0)

Feature Engineering: Calculating new features like "Lost Weight"

One-hot Encoding: For categorical variables (Sex)

Data Normalization & Standardization: Using MinMaxScaler and StandardScaler

Visualization: Bar charts, violin plots, correlation/heatmap graphs to reveal patterns and relationships

Automated Profiling: Using ydata-profiling for quick and thorough data exploration

Feature Importance: Checking feature correlation with Age for future modeling
