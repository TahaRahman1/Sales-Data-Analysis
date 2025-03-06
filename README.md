# 📊 Sales Data Analysis

## 📌 Project Overview
This project focuses on analyzing sales data to uncover trends, insights, and patterns. Using Python and Jupyter Notebook, the analysis includes data cleaning, transformation, and visualization to provide meaningful business insights.

## 📂 Dataset
The dataset used for this analysis contains transaction records, including:
- **Product Categories**
- **Sales Amount**
- **Customer Demographics**
- **Purchase Date**
- **Profit Margins**
- **Location Information**

## 🚀 Features
- **Data Preprocessing**: Cleaning and transforming raw sales data.
- **Exploratory Data Analysis (EDA)**: Identifying trends and patterns.
- **Visualization**: Using Matplotlib and Seaborn to represent sales distribution.
- **Sales Performance Metrics**: Analyzing revenue, profit, and top-selling products.
- **Customer Segmentation**: Understanding customer behavior based on demographics.

## 🛠 Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib & Seaborn** (for visualization)
- **Jupyter Notebook**

## ⚙️ Setup
- Installing Jupyter Notebook: [Jupyter Installation Guide](https://jupyter.readthedocs.io/en/latest/install.html)
- Installing Pandas library: [Pandas Installation Guide](https://pandas.pydata.org/pandas-docs/stable/install.html)

### 🧹 Data Cleaning
We start by cleaning our data. Tasks during this section include:
- Dropping **NaN values** from the DataFrame
- Removing **rows based on a condition**
- Changing the **type of columns** (`to_numeric`, `to_datetime`, `astype`)

### 🔍 Data Exploration
Once we have cleaned up our data, we move to the data exploration section. In this section, we explore **five high-level business questions** related to our data:

1. **What was the best month for sales?** How much was earned that month?
2. **What city sold the most products?**
3. **What time should we display advertisements** to maximize the likelihood of customers buying a product?
4. **What products are most often sold together?**
5. **What product sold the most?** Why do you think it sold the most?

### 📊 Methods Used
To answer these questions, we walk through many different **Pandas** & **Matplotlib** methods, including:
- **Concatenating multiple CSVs** together to create a new DataFrame (`pd.concat`)
- **Adding columns**
- **Parsing cells as strings** to make new columns (`.str`)
- Using the **`.apply()` method**
- Using **`groupby`** to perform aggregate analysis
- **Plotting bar charts and line graphs** to visualize our results
- **Labeling graphs** for better readability

## 📊 Results & Insights
- **Top-selling products** identified based on revenue.
- **Seasonal trends** influencing customer purchases.
- **Regional sales performance** showing high-demand locations.
- **Customer segmentation insights** for targeted marketing.

## 📌 Future Enhancements
- Implement **machine learning** for sales prediction.
- Add an **interactive dashboard** using Plotly or Dash.
- Automate **data updates** with real-time streaming.

## 🤝 Contact & Discussion
If you have any questions or want to discuss the project, feel free to connect! 

---

**Made with ❤️ by Taha Rahman**
