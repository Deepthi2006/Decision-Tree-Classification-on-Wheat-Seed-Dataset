

# Wheat Seed Classification using Decision Trees

This repository contains a machine learning project that classifies different varieties of wheat seeds (Kama, Rosa, and Canadian) based on their geometric properties. The project uses a **Decision Tree Classifier** to achieve high-accuracy predictions.

## 📋 Project Overview

The goal of this project is to categorize wheat seeds into three distinct classes using seven geometric features. This is a classic multiclass classification problem solved using the `Scikit-Learn` library.

## 📊 Dataset

The dataset consists of **210 observations** of wheat kernels. Each observation includes the following features:

* **Area**: The total surface area of the seed.
* **Perimeter**: The distance around the edge of the seed.
* **Compactness**: Calculated as .
* **Length of kernel**: The longitudinal dimension.
* **Width of kernel**: The transverse dimension.
* **Asymmetry coefficient**: Measure of the seed's shape symmetry.
* **Length of kernel groove**: The length of the indentation on the seed.

**Target Classes:** 1. Kama (Class 1)
2. Rosa (Class 2)
3. Canadian (Class 3)

## 🛠️ Tech Stack

* **Language:** Python 3.11
* **Libraries:** * `Pandas` & `NumPy` (Data Manipulation)
* `Matplotlib` & `Seaborn` (Data Visualization)
* `Scikit-Learn` (Machine Learning)



## 🚀 Workflow

1. **Data Cleaning:** Removed redundant columns (`Unnamed: 8`, `Unnamed: 9`) to streamline the feature set.
2. **Exploratory Data Analysis (EDA):** Checked for null values, unique values, and statistical distribution of the features.
3. **Model Training:** * Split the data into Training (80%) and Testing (20%) sets.
* Initialized a `DecisionTreeClassifier` with `gini` criterion and a `max_depth` of 4 to prevent overfitting.


4. **Evaluation:** Generated a classification report and accuracy score to measure performance.
5. **Visualization:** Plotted the decision tree to interpret how the model makes classification decisions.

## 📈 Performance

The model provides a detailed classification report including:

* **Precision**
* **Recall**
* **F1-Score**
* **Overall Accuracy**

## 💻 How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/wheat-seed-classification.git

```


2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```


3. Run the Jupyter Notebook:
```bash
jupyter notebook decision-tree-classification-on-wheat-seed-dataset.ipynb

```



---

Would you like me to help you write a "Conclusion" section based on the specific accuracy results from your notebook?
