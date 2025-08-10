## 🎯 Task: Predict California Housing Prices

### 1. **Dataset**

* Use the **California Housing Prices Dataset** (`fetch_california_housing` in Scikit-learn).
* Features include:

  * `MedInc` → Median income in block
  * `HouseAge` → Median house age
  * `AveRooms`, `AveBedrms` → Average rooms & bedrooms per household
  * `Population`, `AveOccup` → Population & average occupants per household
  * `Latitude`, `Longitude` → Location coordinates
  * `MedHouseVal` → Median house value (target)

---

### 2. **Objectives**

Students will:

1. Perform **EDA** and understand data patterns.
2. Preprocess the dataset for machine learning.
3. Train and evaluate regression models.
4. Interpret and visualize results.

---

### 3. **Tasks**

#### **Task 1 – Data Loading & Exploration**

* Load dataset from `sklearn.datasets`.
* Convert it to a Pandas DataFrame.
* Check shape, data types, and missing values.
* Describe statistical summary.
* Display the first and last 5 rows.

---

#### **Task 2 – EDA (Exploratory Data Analysis)**

* Plot histograms for each feature.
* Check correlations (heatmap).
* Scatter plot of `MedInc` vs `MedHouseVal`.
* Scatter plot of `Latitude` & `Longitude` colored by house value (geo-visualization).
* Identify outliers.

---

#### **Task 3 – Data Preprocessing**

* Handle missing values (if any).
* Scale features using `StandardScaler` or `MinMaxScaler`.
* Split dataset into **train (80%)** and **test (20%)** sets.

---

#### **Task 4 – Model Training**

* Train the following regression models:

  1. **Linear Regression**
  2. **Decision Tree Regressor**
  3. **Random Forest Regressor**
* Evaluate models using:

  * **Mean Absolute Error (MAE)**
  * **Mean Squared Error (MSE)**
  * **R² Score**

---

#### **Task 5 – Model Comparison**

* Create a comparison table of performance metrics.
* Plot feature importance for tree-based models.
* Discuss which features have the most impact.

---

#### **Task 6 – Predictions**

* Predict house prices for **5 random samples** from the test set.
* Compare actual vs predicted values.

---

#### **Task 7 – Insights Report**

* Write **5 key insights** from the dataset and model results.
* Example:

  * "Median income is the strongest predictor of house value."
  * "Houses near the coast have higher prices."

---

### 4. **Deliverables**

1. **Jupyter Notebook** with:

   * Clean, documented code.
   * Visualizations.
   * Analysis.
2. **PDF Report** summarizing:

   * Dataset understanding.
   * Model results & comparison.
   * Key insights.

---

### 5. **Evaluation Criteria**

| Criteria                | Weight |
| ----------------------- | ------ |
| Data Loading & Cleaning | 15%    |
| EDA & Visualizations    | 25%    |
| Model Implementation    | 30%    |
| Model Evaluation        | 15%    |
| Insights & Reporting    | 15%    |

---
