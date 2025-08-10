## 🎯 Task: Sentiment Analysis on Movie Reviews (NLP)

---

### 1. **Dataset**

* Use **IMDb Movie Reviews Dataset** ([Kaggle link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)) or `nltk.corpus.movie_reviews`.
* Columns:

  * `review` → text of the review
  * `sentiment` → `positive` / `negative`

---

### 2. **Objectives**

Students will:

1. Perform **text preprocessing**.
2. Explore text data patterns.
3. Build and evaluate a sentiment classification model.
4. Visualize most common words.

---

### 3. **Tasks**

#### **Task 1 – Data Loading & Exploration**

* Load dataset into Pandas.
* Display basic statistics (count of positive vs negative reviews).
* Print a few sample reviews.

---

#### **Task 2 – Text Preprocessing**

* Convert text to lowercase.
* Remove punctuation, stopwords, and special characters.
* Tokenize the reviews.
* Apply **stemming** or **lemmatization**.
* Optional: Convert to **TF-IDF vectors**.

---

#### **Task 3 – Exploratory Data Analysis (EDA)**

* Most frequent words in positive reviews.
* Most frequent words in negative reviews.
* Plot:

  * Word cloud for positive and negative reviews.
  * Review length distribution.

---

#### **Task 4 – Model Building**

* Train a **Logistic Regression** classifier using:

  * **Bag of Words**
  * **TF-IDF**
* Compare performance with **Naive Bayes**.
* Evaluate using:

  * Accuracy
  * Precision, Recall, F1-score
  * Confusion Matrix

---

#### **Task 5 – Predictions**

* Predict sentiment for **5 new sample reviews**.
* Compare actual vs predicted sentiment (if known).

---

#### **Task 6 – Advanced (Optional)**

* Use **Word Embeddings** (Word2Vec or GloVe).
* Fine-tune a **BERT-based transformer** for sentiment analysis.

---

#### **Task 7 – Insights Report**

* Write **5 key insights** from analysis.

  * Example:

    * “Positive reviews often use words like ‘amazing’, ‘wonderful’, ‘excellent’.”
    * “Negative reviews frequently contain words like ‘boring’, ‘waste’, ‘worst’.”

---

### 4. **Deliverables**

1. **Jupyter Notebook**:

   * Preprocessing, EDA, modeling, evaluation.
2. **PDF Report**:

   * Summary of findings
   * Model comparison
   * Recommendations

---

### 5. **Evaluation Criteria**

| Criteria              | Weight |
| --------------------- | ------ |
| Text Preprocessing    | 20%    |
| EDA & Visualization   | 20%    |
| Model Implementation  | 30%    |
| Evaluation & Insights | 20%    |
| Code Quality          | 10%    |

---