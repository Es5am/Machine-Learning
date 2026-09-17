# Machine Learning

A practical Machine Learning section containing implementations and experiments based on a series of six lectures.

The notebooks focus on building a strong foundation in Machine Learning, from data preprocessing and regression to classification, advanced models, unsupervised learning, model optimization, and evaluation.

---

## 📚 Lecture Overview

| Lecture | Notebook                    | Main Topics                                                           |
| ------- | --------------------------- | --------------------------------------------------------------------- |
| **S1**  | `S1_Machine_Learning.ipynb` | ML Foundations, Data Preprocessing, Encoding, Scaling                 |
| **S2**  | `S2_Machine_Learning.ipynb` | Linear Regression, OLS, Gradient Descent, Regression Metrics          |
| **S3**  | `S3_Machine_Learning.ipynb` | Logistic Regression, Classification Metrics, ROC & AUC                |
| **S4**  | `S4_Machine_Learning.ipynb` | KNN, SVM, Decision Trees, Random Forest                               |
| **S5**  | `S5_Machine_Learning.ipynb` | K-Means, PCA, Cross-Validation, Hyperparameter Tuning, Regularization |
| **S6**  | `S6_Machine_Learning.ipynb` | *To be documented*                                                    |

---

## 🎯 Learning Objectives

This section focuses on developing practical Machine Learning skills through hands-on notebook implementations.

The main objectives are to:

* Understand the fundamental Machine Learning workflow.
* Prepare and preprocess real-world datasets.
* Handle missing values and categorical features.
* Apply feature encoding and scaling techniques.
* Build regression and classification models.
* Understand the mathematical foundations behind common algorithms.
* Evaluate models using appropriate performance metrics.
* Work with distance-based, tree-based, and ensemble models.
* Explore unsupervised learning techniques.
* Reduce feature dimensionality using PCA.
* Optimize model hyperparameters.
* Apply cross-validation techniques.
* Understand overfitting, underfitting, and regularization.
* Build a structured approach to Machine Learning experimentation.

---

## 🧠 Topics Covered

### 1. Machine Learning Foundations

The first lecture establishes the basic Machine Learning workflow and introduces the main learning paradigms:

* Supervised Learning
* Unsupervised Learning
* Dataset inspection
* Data types and dataset dimensions
* Data preprocessing
* Missing-value handling
* Feature type conversion
* Label Encoding
* One-Hot Encoding
* Train-Test Split
* Feature Scaling
* Standardization
* Normalization

---

### 2. Linear Regression

The second lecture focuses on regression problems and the mathematical foundations behind Linear Regression.

Topics include:

* Simple Linear Regression
* Multiple Linear Regression
* Ordinary Least Squares (OLS)
* Loss / Cost Functions
* Gradient Descent
* Iterative parameter optimization
* Regression model evaluation

### Regression Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* $R^2$
* Adjusted $R^2$

---

### 3. Logistic Regression

The third lecture introduces binary classification using Logistic Regression.

Topics include:

* Binary Classification
* Logistic Regression
* Hypothesis formulation
* Sigmoid Function
* Probability prediction
* Decision Thresholds
* Classification boundaries

### Classification Metrics

* Confusion Matrix
* Accuracy
* Precision
* Recall
* F1-Score
* ROC Curve
* AUC

---

### 4. Advanced Supervised Learning Models

The fourth lecture explores several widely used Machine Learning algorithms.

#### K-Nearest Neighbors (KNN)

* Distance-based learning
* KNN Classification
* KNN Regression
* Distance Metrics

#### Support Vector Machines (SVM)

* Hyperplanes
* Margins
* Margin Maximization
* Kernel Methods

#### Decision Trees

* Tree-based learning
* Node Splitting
* Gini Impurity
* Entropy
* Information Gain

#### Random Forest

* Ensemble Learning
* Bagging
* Multiple Decision Trees
* Random Forest Models

---

### 5. Unsupervised Learning & Model Optimization

The fifth lecture combines unsupervised learning with techniques for improving model performance and generalization.

#### Clustering

* Unsupervised Learning
* K-Means Clustering

#### Dimensionality Reduction

* Principal Component Analysis (PCA)
* Feature Compression

#### Hyperparameter Optimization

* Grid Search
* `GridSearchCV`
* Random Search
* `RandomizedSearchCV`

#### Cross-Validation

* K-Fold Cross-Validation
* Model validation strategies

#### Regularization

* Overfitting
* Underfitting
* Generalization
* L1 Regularization
* Lasso Regression
* L2 Regularization
* Ridge Regression

---

## 🔄 Machine Learning Workflow

The lectures progressively build a practical Machine Learning workflow:

```text
Dataset
   │
   ▼
Data Inspection
   │
   ▼
Data Preprocessing
   │
   ├── Missing Values
   ├── Type Conversion
   └── Categorical Encoding
   │
   ▼
Feature Engineering / Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Selection
   │
   ├── Regression
   ├── Classification
   └── Clustering
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Cross-Validation
   │
   ▼
Hyperparameter Optimization
   │
   ▼
Regularization & Generalization
   │
   ▼
Final Model
```

---

## 🛠️ Technologies & Libraries

The notebooks are based primarily on the Python Machine Learning ecosystem.

| Technology           | Purpose                                     |
| -------------------- | ------------------------------------------- |
| **Python**           | Programming language                        |
| **Jupyter Notebook** | Interactive development and experimentation |
| **NumPy**            | Numerical computing                         |
| **Pandas**           | Data manipulation and analysis              |
| **Matplotlib**       | Data visualization                          |
| **Scikit-learn**     | Machine Learning algorithms and utilities   |

---

## 📂 Directory Structure

```text
Machine Learning/
│
├── README.md
│
├── S1_Machine_Learning.ipynb
├── S2_Machine_Learning.ipynb
├── S3_Machine_Learning.ipynb
├── S4_Machine_Learning.ipynb
├── S5_Machine_Learning.ipynb
└── S6_Machine_Learning.ipynb
```

---

## 🚀 Running the Notebooks

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### 5. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open the desired notebook:

```text
S1_Machine_Learning.ipynb
```

through

```text
S6_Machine_Learning.ipynb
```

---

## 📈 Learning Progression

The six lectures are structured as a progressive learning path:

```text
Machine Learning Foundations
          │
          ▼
    Linear Regression
          │
          ▼
   Logistic Regression
          │
          ▼
Advanced ML Algorithms
          │
          ▼
Unsupervised Learning
          │
          ▼
Optimization & Generalization
```

This progression connects the fundamental Machine Learning workflow with increasingly advanced modeling and evaluation techniques.

---

## 📝 Notes

* Each notebook represents practical work associated with the corresponding lecture.
* The notebooks are intended for learning, experimentation, and implementation practice.
* The examples demonstrate Machine Learning workflows rather than representing production-ready ML systems.
* Dataset-specific results may vary depending on the data and configuration used in each notebook.
* The notebooks can be revisited and extended as new Machine Learning concepts are learned.

---

## 📌 Key Skills Practiced

Through these lectures, the practical focus includes:

* Data preprocessing
* Feature encoding
* Feature scaling
* Regression
* Classification
* Model evaluation
* Clustering
* Dimensionality reduction
* Cross-validation
* Hyperparameter tuning
* Regularization
* Model generalization
* Machine Learning workflow design

---

> **Learn the theory. Implement the algorithm. Evaluate the model. Improve the solution.**
