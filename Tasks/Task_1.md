## 🎯 Task: Movie Recommendation & Insights using MovieLens Dataset

### 1. **Dataset**

* Use the **MovieLens 100K dataset** ([link](https://grouplens.org/datasets/movielens/)).
* Dataset files:

  * `u.data` → ratings (user, movie, rating, timestamp)
  * `u.item` → movie information
  * `u.user` → user demographic info

---

### 2. **Objectives**

Students will:

1. Load and explore the dataset.
2. Perform **Exploratory Data Analysis (EDA)**.
3. Build a **simple recommender system**.
4. Visualize results and provide insights.

---

### 3. **Tasks**

#### **Task 1 – Data Loading & Cleaning**

* Load the dataset into Pandas DataFrames.
* Merge ratings with movie titles.
* Handle missing values (if any).
* Convert timestamps to readable dates.

---

#### **Task 2 – Exploratory Data Analysis**

* Show **top 10 most rated movies**.
* Show **top 10 highest-rated movies** (with a minimum of 50 ratings).
* Plot:

  * Distribution of ratings (histogram).
  * Average rating per genre.
  * Number of ratings per year.

---

#### **Task 3 – Basic Recommendation System**

**A. Popularity-Based Recommender**

* Recommend movies with the highest average rating (min 100 ratings).

**B. Collaborative Filtering (User-User)**

* Use the `pivot_table` to create a user-movie ratings matrix.
* Calculate **Pearson correlation** between users.
* Recommend movies to a given user based on similar users’ preferences.

---

#### **Task 4 – Advanced (Optional)**

* Implement **Item-Item Collaborative Filtering**.
* Use **Cosine Similarity** instead of Pearson.
* Try a **content-based filter** using genres.

---

#### **Task 5 – Insights Report**

* Write **5 key insights** from your analysis.
* Example:

  * "Action movies tend to have higher variance in ratings."
  * "Older movies are rated higher by older users."

---

### 4. **Deliverables**

1. **Jupyter Notebook** with:

   * Clean, well-commented code.
   * Visualizations.
   * Explanations.
2. **PDF Report** summarizing insights and recommendations.

---

### 5. **Evaluation Criteria**

| Criteria                   | Weight |
| -------------------------- | ------ |
| Data Loading & Cleaning    | 15%    |
| EDA & Visualizations       | 25%    |
| Recommender Implementation | 35%    |
| Insights & Report          | 15%    |
| Code Quality               | 10%    |

---
