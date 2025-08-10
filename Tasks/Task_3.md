## 🎯 Task: Retail Sales Analysis & Forecasting

---

### 1. **Dataset**

* Use a dataset such as **Sample – Superstore** ([Kaggle link](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) or Tableau’s default “Sample – Superstore” CSV).
* Common columns:

  * `Order ID`, `Order Date`, `Ship Date`
  * `Category`, `Sub-Category`, `Product Name`
  * `Sales`, `Quantity`, `Discount`, `Profit`
  * `Region`, `State`, `City`, `Segment`

---

### 2. **Objectives**

Students will:

1. Perform **EDA** to find sales trends and patterns.
2. Analyze **top-performing products & regions**.
3. Build **sales prediction models**.
4. Create **visual dashboards**.

---

### 3. **Tasks**

#### **Task 1 – Data Loading & Cleaning**

* Load dataset into Pandas.
* Convert `Order Date` & `Ship Date` to datetime.
* Handle missing values.
* Remove duplicates if any.

---

#### **Task 2 – Exploratory Data Analysis**

* Total sales, profit, and quantity by:

  * **Category**
  * **Region**
  * **Month/Year**
* Identify **top 10 products** by sales.
* Find **most profitable categories**.
* Analyze the effect of **discounts on profit**.

---

#### **Task 3 – Time Series Analysis**

* Group sales by **month** and plot trends.
* Identify seasonal patterns.
* Use **rolling averages** to smooth data.

---

#### **Task 4 – Predictive Modeling**

**Option A: Regression Model**

* Predict **Sales** using features like Quantity, Discount, Category, and Region.
* Try **Linear Regression** and **Random Forest**.

**Option B: Time Series Forecast**

* Use monthly aggregated sales data.
* Apply **ARIMA** or **Facebook Prophet** for forecasting.

---

#### **Task 5 – Visualization Dashboard**

* Use **Matplotlib** / **Seaborn** for:

  * Monthly sales trend
  * Sales by category pie chart
  * Region-wise sales bar chart
  * Discount vs profit scatter plot

---

#### **Task 6 – Insights Report**

* Write **5–7 key business insights**.

  * Example:

    * “High discounts often lead to negative profits.”
    * “Technology category has the highest profit margin.”
    * “Western region contributes the largest share of sales.”

---

### 4. **Deliverables**

1. **Jupyter Notebook**:

   * Code with comments
   * EDA visualizations
   * Predictive modeling
2. **PDF Report**:

   * Summary of findings
   * Recommendations for the business

---

### 5. **Evaluation Criteria**

| Criteria                    | Weight |
| --------------------------- | ------ |
| Data Cleaning & Preparation | 15%    |
| EDA & Visualizations        | 25%    |
| Modeling & Predictions      | 30%    |
| Insights & Recommendations  | 20%    |
| Code Quality                | 10%    |

---