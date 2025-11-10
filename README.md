# TOURISIM_EDA-CAPSTONE_PROJECT-EDA_1
This project performs Exploratory Data Analysis (EDA) on tourism data to uncover key insights about travel trends, visitor ratings, production/earnings, and continent-level statistics. It helps understand patterns and relationships that can support tourism management, marketing strategies, and policy decisions.

<h3>INTRODUCTION</h3>
The Tourism Data EDA project aims to explore and analyze global tourism patterns from 2010–2024.
Through Exploratory Data Analysis (EDA), we gain insights into visitor trends, tourism revenue, and how different factors affect the tourism industry.

<h3>Dataset</h3>
File Name: tourism_dataset.csv

Description: Contains data related to global tourism such as:

Country and Continent

Number of Tourist Arrivals

Tourism Revenue

Year-wise data

Data Type: Mixed (Categorical + Numerical)

Goal: Clean, visualize, and extract meaningful insights.

<h3>Libraries used</h3>
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

<h3>Data Cleaning</h3>
Data cleaning ensures accuracy and consistency before performing analysis.
Steps performed:

1.Checked for missing values and duplicates

2.Renamed inconsistent column names

3.Converted data types (e.g., Year to integer)

4.Handled outliers using boxplots

5.Removed unnecessary or redundant columns

df.isnull().sum()
df.duplicated().sum()
df.info()
df.describe()

<h3>Univariate Analysis</h3>
Analyzed single variables to understand their distribution and characteristics.

Methods:

Histograms for numerical columns

Countplots for categorical columns

Summary statistics using .describe()

<h3>Bivariate Analysis</h3>
Examined the relationship between two variables at a time.

Methods:

Scatter plots for correlation

Pair plots for overall relationships

Heatmap for correlation matrix


<h3>Key Findings</h3>
Europe and Asia generated the highest tourism revenue.

Tourist Arrivals and Revenue are strongly correlated.

2020 saw a significant drop in tourism activity (global pandemic impact).

Some countries show strong recovery trends post-2021.

<h3>Author</h3>
Abdul rahman

email:abdrah1264@gmail.com




