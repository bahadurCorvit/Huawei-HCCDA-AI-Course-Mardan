## 🎯 Task: Build a Chatbot (Rule-based → AI-based)

---

### 1. **Dataset Options**

* **Cornell Movie Dialogs Dataset** ([link](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html))
* **Kaggle ChatterBot Dataset** ([link](https://www.kaggle.com/datasets/gauravsharma99/chatbot-dataset))
* Or a **custom FAQ dataset** (CSV format: `question`, `answer`).

---

### 2. **Objectives**

Students will:

1. Learn **text preprocessing** for conversations.
2. Build **Rule-based Chatbot** (simple Q\&A).
3. Build **ML/DL-based Chatbot** (intent classification).
4. Test chatbot on custom inputs.

---

### 3. **Tasks**

#### **Task 1 – Data Preparation**

* Load dataset into Pandas.
* Check number of dialogues.
* If no dataset, create a **mini FAQ dataset**:

  ```csv
  question,answer
  What is AI?,AI stands for Artificial Intelligence...
  Who created Python?,Python was created by Guido van Rossum...
  ```

---

#### **Task 2 – Rule-Based Chatbot**

* Use **if-else conditions** or **dictionary mapping**.
* Match user input to closest question (string similarity / regex).
* Respond with pre-defined answers.
* Add fallback message if no match is found.

---

#### **Task 3 – NLP Preprocessing**

* Lowercasing, removing punctuation, stopwords.
* Tokenization.
* Lemmatization or stemming.
* Convert text to **Bag of Words** or **TF-IDF**.

---

#### **Task 4 – AI-Based Chatbot (Intent Classification)**

* Label each question with an **intent** (e.g., greeting, weather, goodbye).
* Split into train/test.
* Train a **classifier** (Logistic Regression / SVM / Naive Bayes) to predict intent.
* Map predicted intent to a pre-defined response.

---

#### **Task 5 – Deep Learning Chatbot (Optional Advanced)**

* Use **RNN / LSTM** with embedding layers.
* Train on a conversation dataset.
* Or fine-tune **DialoGPT** or **ChatGPT API** for responses.

---

#### **Task 6 – Interactive Mode**

* Use a `while True` loop for continuous chatting:

  ```python
  while True:
      user_input = input("You: ")
      if user_input.lower() in ["quit", "exit"]:
          break
      response = chatbot_response(user_input)
      print("Bot:", response)
  ```

---

#### **Task 7 – Evaluation**

* Test chatbot with 10 different user queries.
* Measure:

  * Response accuracy
  * Fallback rate (how often bot fails to answer)
  * User satisfaction (manual feedback)

---

#### **Task 8 – Insights Report**

* Advantages & limitations of the chatbot.
* Possible improvements (context handling, sentiment awareness, multi-turn memory).

---

### 4. **Deliverables**

1. **Jupyter Notebook**:

   * Rule-based + AI-based chatbot.
2. **Short Video Demo** (optional).
3. **PDF Report**:

   * How chatbot works.
   * Challenges faced.
   * Next improvements.

---

### 5. **Evaluation Criteria**

| Criteria                   | Weight |
| -------------------------- | ------ |
| Data Preparation           | 15%    |
| Rule-Based Implementation  | 15%    |
| AI-Based Implementation    | 30%    |
| Interactive Mode & Testing | 20%    |
| Insights & Documentation   | 15%    |
| Code Quality               | 5%     |
