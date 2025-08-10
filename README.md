# Product_Sales_Analysis-Pens-and-Printers

## 📌 Project Overview
This project analyzes sales performance for **Pens and Printers**, a company founded in 1984 that provides high-quality office products to large organizations. The main focus is on evaluating the effectiveness of different sales methods for a **new line of office stationery** launched six weeks ago.  

The three tested sales strategies are:
- **Email** – Two emails sent over three weeks.
- **Call** – Direct phone calls (~30 minutes per customer).
- **Email + Call** – Email followed by a shorter (~10 minutes) follow-up call.

The analysis focuses on:
- Data validation & cleaning
- Sales performance comparison
- Customer segmentation
- Revenue impact of different sales strategies

---

## 📂 Project Structure
```
Product_Sales.ipynb    # Main analysis notebook
product_sales.csv      # Dataset used for analysis (not included here)
README.md              # Project documentation
```

---

## 🔍 Data Validation & Cleaning
The following checks and cleaning steps were applied:
1. **Data Types** – Ensured correct column types (e.g., `week` as `int64`, `revenue` as `float64`).
2. **Missing Values** – Found and imputed 1,074 missing `revenue` values.
3. **Categorical Standardization** – Normalized inconsistent `sales_method` entries (`'email'` → `'Email'`).
4. **Duplicates** – Checked for duplicates (none found).
5. **Numeric Range Validation** – Ensured `nb_sold >= 0`, `revenue >= 0`, and logical customer years.
6. **State Validation** – Verified all US state codes were valid.
7. **Week Validation** – Confirmed all weeks were between 1 and 6.

---

## 📊 Analysis & Insights
- Sales performance was compared across the three methods.
- Visualizations were created to show:
  - Revenue trends
  - Number of products sold
  - Customer retention by method
- Statistical methods were used to assess significance between strategies.

---

## 🛠️ Technologies Used
- **Python** – Data analysis and visualization
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Visualizations
- **Jupyter Notebook** – Analysis workflow

---

## 📈 Future Improvements
- Automate data validation and cleaning steps.
- Add predictive modeling for future sales performance.
- Incorporate customer demographic data for deeper insights.

---

## 📜 License
This project is for educational and analytical purposes.
