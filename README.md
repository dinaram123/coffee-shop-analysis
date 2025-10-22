Coffee Shop Sales Analysis

This project provides an Exploratory Data Analysis (EDA) of coffee shop sales to uncover patterns, customer behavior, and business insights. It uses Python libraries like Pandas, Matplotlib, and Seaborn to visualize trends and summarize performance metrics.

 Objectives

The main goals of this project are:

To analyze daily, weekly, and monthly sales trends.
To identify the best-selling coffee types and peak sales hours.
To understand customer preferences by payment type and product category.
To support business decisions such as menu optimization and pricing.
 Project Structure
coffee-shop-analysis/

│── coffee_sales.csv          # Dataset
│── README.md
| dash
│── 01-exploratory-analysis.ipynb  # Jupyter notebook (EDA)           
└── README.md

 Key Insights
Latte and Cappuccino are consistently top-selling items.
Fridays and Saturdays record the highest revenue.
Most customers prefer card payments over cash.
Monthly revenue trends show seasonality with peaks around holidays.
 Technologies Used
Python 3.10+
Pandas – Data manipulation
NumPy – Numerical analysis
Matplotlib & Seaborn – Data visualization
Plotly – Interactive plots
Jupyter Notebook – Exploratory workflow
 How to Run

Clone the repository:

git clone https://github.com/<your-username>/coffee-shop-analysis.git
cd coffee-shop-analysis


Install dependencies:

pip install -r requirements.txt


Run the analysis script:

python src/eda.py --data data/coffee_sales.csv --out outputs/


Or explore interactively using Jupyter:

jupyter lab

 Example Visualizations
Monthly sales trends
Top 10 selling coffee items
Sales distribution by payment type
Revenue by day of the week



All generated charts are saved under the outputs/ folder.

 Next Steps
Add machine learning models for demand forecasting
Create dashboards using Plotly or Power BI
Incorporate customer segmentation and loyalty analysis
 License

This project is released under the MIT License — you are free to use, modify, and distribute it.


