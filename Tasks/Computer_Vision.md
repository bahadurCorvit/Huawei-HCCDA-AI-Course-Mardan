## 🎯 Task: Image Classification Using CNNs

---

### 1. **Dataset Options**

* **CIFAR-10** (available in `tensorflow.keras.datasets`)
* **Fashion MNIST** (28×28 grayscale clothing images)
* **Custom dataset** (e.g., downloaded from Kaggle: Cats vs Dogs, Plant Diseases, etc.)

---

### 2. **Objectives**

Students will:

1. Understand image datasets and preprocessing.
2. Build a **Convolutional Neural Network (CNN)** for classification.
3. Train, evaluate, and improve the model.
4. Visualize performance metrics.

---

### 3. **Tasks**

#### **Task 1 – Data Loading & Exploration**

* Load dataset into Python (TensorFlow/Keras or PyTorch).
* Display dataset shape.
* Show **first 10 sample images** with labels.

---

#### **Task 2 – Image Preprocessing**

* Normalize pixel values (0–1 range).
* Convert labels to **one-hot encoding**.
* Optionally apply **data augmentation**:

  * Rotation
  * Flipping
  * Zoom
  * Brightness adjustment

---

#### **Task 3 – Model Building**

* Create a CNN architecture:

  * Convolution layers (Conv2D)
  * Pooling layers (MaxPooling2D)
  * Dropout layers
  * Fully connected (Dense) layer
* Compile with:

  * Optimizer: `adam`
  * Loss: `categorical_crossentropy`
  * Metrics: `accuracy`

---

#### **Task 4 – Model Training**

* Split into **train/test** sets.
* Train for **10–20 epochs**.
* Track training & validation accuracy/loss.

---

#### **Task 5 – Model Evaluation**

* Evaluate on **test dataset**:

  * Accuracy
  * Confusion matrix
  * Classification report (Precision, Recall, F1-score)

---

#### **Task 6 – Visualization**

* Plot training vs validation **accuracy**.
* Plot training vs validation **loss**.
* Show **misclassified images** with predicted vs actual labels.

---

#### **Task 7 – Improvement & Experimentation**

* Try:

  * More CNN layers
  * Data augmentation
  * Transfer learning (MobileNetV2, VGG16)
* Compare results.

---

#### **Task 8 – Insights Report**

* Best accuracy achieved.
* Which classes were hardest to predict?
* How augmentation affected accuracy.

---

### 4. **Deliverables**

1. **Jupyter Notebook**:

   * Data loading, preprocessing, training, evaluation.
2. **PDF Report**:

   * Summary of model performance & key insights.
3. **Trained Model File** (`.h5` or `.pt`).

---

### 5. **Evaluation Criteria**

| Criteria                     | Weight |
| ---------------------------- | ------ |
| Data Loading & Preprocessing | 20%    |
| Model Architecture           | 25%    |
| Training & Evaluation        | 25%    |
| Visualization & Insights     | 20%    |
| Code Quality                 | 10%    |

---