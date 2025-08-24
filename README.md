# 🛒 Blinkit Sales Analysis (Python & Jupyter Notebook)
# 📌 Project Overview

This project analyzes Blinkit sales data to generate insights about product sales, outlet performance, and customer preferences.
The goal is to clean the dataset, prepare it for analysis, and derive key KPIs useful for decision-making.

📂 Dataset Information

The dataset contains the following key columns:

Item Identifier → Unique product code

Item Fat Content → Fat content category (Low Fat, Regular)

Item Type → Type of product (e.g., Dairy, Snack Foods, etc.)

Outlet Identifier → Unique store code

Outlet Type → Grocery Store, Supermarket, etc.

Outlet Location Type → Tier 1 / Tier 2 / Tier 3 cities

Item Weight, Item Visibility, Sales, Rating

# 🛠️ Data Cleaning

Standardized Item Fat Content values (merged “LF”, “low fat” → “Low Fat”; “reg” → “Regular”).

#Handled missing values and ensured consistent data formatting.

Converted categorical variables where necessary for analysis.

🎯 Business Requirements & KPIs

The following KPIs were defined for analysis:

✅ Total Sales across all outlets

✅ Average Sales per Outlet

✅ Sales by Item Type

✅ Sales by Outlet Type & Location

✅ Impact of Item Fat Content on Sales

✅ Outlet Rating Performance

🔎 Insights (Sample Findings)

📌 Regular fat items contributed more sales compared to Low Fat.
📌 Tier 3 locations showed the highest average sales.
📌 Certain item categories (Snacks, Fruits, Frozen Foods) performed better across all outlet types.

# 🛠️ Tools & Libraries

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook (for EDA & visualization)


 # 🚀 How to Run

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn


Open Jupyter Notebook:

jupyter notebook Blinkit_Analysis_Project.ipynb

👩‍💻 Author

Harshita Bisht
