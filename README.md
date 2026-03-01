🍽️ Zomato Restaurant Data Analysis

📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Zomato restaurant dataset using Python.

The goal is to clean, preprocess, and analyze restaurant data to understand customer behavior, ratings, cost distribution, and service availability.

⚠️ Note:

This project is for Data Analysis purposes only.

No Machine Learning models were built.

📂 Dataset

Dataset used:

Zomato-data-.csv

Main Features:

name (Restaurant Name)

online_order

book_table

rate

votes

approx_cost (for two people)

listed_in(type)

🛠️ Technologies Used

Python 🐍

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn (for preprocessing only)

🔎 Data Cleaning & Preprocessing

1️⃣ Data Inspection

Checked dataset shape and info

Identified missing values

Checked duplicates

Explored value counts

2️⃣ Handling Ratings

Removed /5 from rate column

Converted rating to float

3️⃣ Encoding Binary Columns

Converted:

online_order → Yes = 1, No = 0

book_table → Yes = 1, No = 0

4️⃣ Handling Zero Values

Replaced 0 values with median in:

votes

approx_cost(for two people)

5️⃣ Feature Engineering

Dropped unnecessary column: name

Applied LabelEncoder on listed_in(type)

6️⃣ Feature Scaling

Used MinMaxScaler on:

votes

approx_cost (for two people)

📊 Exploratory Data Analysis (EDA)

Key analysis performed:

Distribution of restaurant types

Rating distribution

Online order vs Book table availability

Cost analysis

Correlation analysis between numerical features

Generated:

Value counts

Statistical summaries

Correlation matrix

📈 Key Insights (Example)

Most restaurants fall under specific dining categories.

Ratings cluster around mid-to-high range.

Online ordering is more common than table booking.

Votes and cost show moderate correlation with rating.
