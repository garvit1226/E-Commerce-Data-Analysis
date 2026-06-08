# 🛒 E-Commerce Data Analysis

An Exploratory Data Analysis (EDA) project on the Superstore dataset using Python. The project analyzes sales and profit trends, product category performance, customer segments, and business insights through data visualization.

## 📌 Project Overview

This project focuses on understanding the sales and profitability of an e-commerce business. Various visualizations and statistical summaries are used to identify patterns, trends, and opportunities for business growth.

## 🎯 Objectives

- Perform data cleaning and preprocessing
- Analyze monthly sales trends
- Analyze monthly profit trends
- Identify top-performing product categories
- Explore sub-category sales distribution
- Compare profit across categories
- Study Sales-to-Profit relationships
- Generate actionable business insights

---

## 📂 Project Structure

```
E-Commerce/
│
├── data/
│   └── Sample - Superstore.csv
│
├── images/
│   ├── Monthly sale analysis.png
│   ├── Monthly Profit.png
│   ├── Sales based on product categories.png
│   ├── Sales based on sub categories.png
│   └── Profit by Categories.png
│
├── E_commerce_Data_Analysis.ipynb
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Analysis Performed

### 1. Data Preprocessing
- Loaded Superstore dataset
- Checked data types and missing values
- Converted date columns into datetime format
- Created additional columns:
  - Year
  - Month
  - Day of Week

### 2. Monthly Sales Analysis
- Visualized monthly sales distribution
- Identified months with highest and lowest sales

### 3. Sales by Product Categories
- Compared sales across categories:
  - Furniture
  - Office Supplies
  - Technology

### 4. Sales by Sub-Categories
- Analyzed revenue contribution of individual sub-categories

### 5. Monthly Profit Analysis
- Examined monthly profit fluctuations
- Identified profitable periods

### 6. Profit by Categories
- Compared profitability among product categories

### 7. Sales-to-Profit Analysis
- Evaluated how sales translate into profit across customer segments

---

## 📈 Key Insights

- Technology category generated the highest revenue.
- Certain months showed significantly higher sales and profit.
- Some high-selling products contributed relatively lower profits.
- Customer segments exhibited different profit margins.
- Sales growth does not always guarantee profit growth.

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/garvit1226/E-Commerce-Data-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```bash
E_commerce_Data_Analysis.ipynb
```

---

## 📷 Visualizations

The project includes:

- Monthly Sales Analysis
- Monthly Profit Analysis
- Sales by Categories
- Sales by Sub-Categories
- Profit by Categories

All generated charts are available inside the `images/` folder.

---

## 📚 Dataset

Dataset Used: **Sample Superstore Dataset**

The dataset contains information about:

- Orders
- Sales
- Profit
- Customers
- Product Categories
- Shipping Details

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a Pull Request

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
