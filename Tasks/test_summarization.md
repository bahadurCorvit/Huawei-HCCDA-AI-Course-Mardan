## 🎯 Task: Automatic Text Summarization

---

### 1. **Dataset**

* **CNN/DailyMail Dataset** ([Hugging Face link](https://huggingface.co/datasets/cnn_dailymail))
  OR
* Any custom dataset of news articles, blog posts, or Wikipedia articles.
  Columns:

  * `article` → full text
  * `highlights` → human-written summary (for evaluation)

---

### 2. **Objectives**

Students will:

1. Understand **text summarization techniques**.
2. Preprocess and analyze long text documents.
3. Implement **Extractive Summarization**.
4. Implement **Abstractive Summarization**.
5. Compare model results with human summaries.

---

### 3. **Tasks**

#### **Task 1 – Data Loading & Exploration**

* Load dataset (or scrape 50+ articles using Python).
* Check dataset size, sample articles, and summaries.
* Print 2 examples of article + reference summary.

---

#### **Task 2 – Text Preprocessing**

* Convert text to lowercase.
* Remove stopwords and punctuation.
* Tokenize into sentences and words.
* Optional: Apply lemmatization.

---

#### **Task 3 – Extractive Summarization**

**Option A: Frequency-based**

* Calculate word frequencies (excluding stopwords).
* Score sentences based on sum of word frequencies.
* Pick top `n` sentences as the summary.

**Option B: TextRank Algorithm**

* Use `sumy` or `gensim.summarization`.
* Generate summaries with different compression ratios.

---

#### **Task 4 – Abstractive Summarization**

**Option A: Pre-trained Transformer**

* Use **Hugging Face Transformers** (`facebook/bart-large-cnn` or `t5-small`).
* Tokenize, feed text to model, generate summary.
* Control summary length.

**Option B: Fine-tuning (Optional Advanced)**

* Fine-tune T5/BART on the dataset.

---

#### **Task 5 – Evaluation**

* Compare model summaries with human-written summaries using:

  * **ROUGE score**
  * **BLEU score**
* Collect **human feedback** for 5–10 samples.

---

#### **Task 6 – Insights Report**

* Summarize:

  * Differences between extractive & abstractive approaches.
  * Cases where one method performed better.
  * Recommendations for real-world usage.

---

### 4. **Deliverables**

1. **Jupyter Notebook**:

   * Preprocessing, summarization, evaluation.
2. **PDF Report**:

   * Summary quality comparison
   * Key findings
3. **Example Output File**:

   * Original text, extractive summary, abstractive summary.

---

### 5. **Evaluation Criteria**

| Criteria           | Weight |
| ------------------ | ------ |
| Data Preprocessing | 15%    |
| Extractive Model   | 20%    |
| Abstractive Model  | 25%    |
| Evaluation         | 20%    |
| Insights & Report  | 15%    |
| Code Quality       | 5%     |

---