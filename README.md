Sales Data Analysis Using Python, Pandas & Matplotlib

This project focuses on analyzing a sales dataset using Python, Pandas, and Matplotlib.
It includes data cleaning, manipulation, exploration, and extraction of useful business insights.



 Dataset

The dataset contains sales records with the following columns:

OrderID

Product

Category

Price

Quantity

Date



 Steps Performed

1. Importing Libraries & Loading Data

import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv("sales_dataset.csv")


2. Data Inspection

Displaying first and last rows

Checking missing values

Checking duplicated rows

Displaying data types

General dataset overview



3. Data Cleaning

Converting Price to numeric

Converting Date to datetime

Filling missing prices with the mean

Removing duplicated rows

Checking for outliers



4. Feature Engineering

New columns created:

Revenue = Quantity × Price

Day (weekday name)

Month (month name)


5. Grouping & Insights Extraction

Grouped revenue by:

Day

Product

Category


Identified:

📈 Best Day

📉 Worst Day

🏆 Best-Selling Product

💤 Lowest-Selling Product



6. Data Visualization

Three main charts were created:

📈 Revenue by Day (Line chart)

📊 Revenue by Product (Bar chart)

🥧 Revenue Share by Category (Pie chart)



---

 Key Insights

✔ The highest revenue day was: Thursday
✔ The lowest revenue day was: Sunday
✔ The best-selling product: Shoes
✔ Category with highest revenue: Fashion




 Technologies Used

Python

Pandas

Matplotlib



---

🎯 Project Goal

To practice real-world data analysis skills and generate business insights that help companies understand:

Best days for sales

Product performance

Category contribution

Revenue trends



📌 How to Run the Project

pip install pandas matplotlib
python analysis.ipynb



🧑‍💻 Author

ZAKARIA SBIKA – Data Analyst (Beginner Level Portfolio)
