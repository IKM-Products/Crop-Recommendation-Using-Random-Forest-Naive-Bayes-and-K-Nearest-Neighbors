# 🌱 Crop Recommendation Using Random Forest, Naive Bayes and K-Nearest Neighbors (Research)

**Crop Recommendation Using Random Forest, Naive Bayes and K-Nearest Neighbors** is a machine learning research study that compares multiple classification algorithms for recommending suitable crops based on soil and climatic parameters. The study evaluates Random Forest, Naive Bayes, and K-Nearest Neighbors using a publicly available crop recommendation dataset, applying data preprocessing, cross-validation, hyperparameter optimization, and standard evaluation metrics to analyze and compare model performance.

## 🔬 Research Focus

The research focuses on evaluating machine learning classification techniques for crop recommendation using the following input parameters:

* 🌱 Nitrogen (N)
* 🌱 Phosphorus (P)
* 🌱 Potassium (K)
* 🌡️ Temperature
* 💧 Humidity
* 🧪 pH
* 🌧️ Rainfall

## 📊 Dataset

The study uses a publicly available crop recommendation dataset containing:

* **2,200 samples**
* **22 crop classes**
* **7 input features**
* **1 target variable** — recommended crop

## 🚀 Research Workflow

1. 📥 **Dataset Collection** - Load the publicly available crop recommendation dataset.
2. 🧹 **Data Preprocessing** - Inspect data quality, missing values, duplicates, and feature distributions.
3. 🎯 **Feature & Target Separation** - Separate the seven input parameters from the crop labels.
4. ✂️ **Data Splitting** - Divide the dataset into training and testing sets.
5. ⚖️ **Feature Scaling** - Apply StandardScaler to the K-Nearest Neighbors model because of its distance-based nature.
6. 🤖 **Model Training** - Train Random Forest, Naive Bayes, and K-Nearest Neighbors classifiers.
7. 🔧 **Hyperparameter Optimization** - Optimize model parameters using search techniques and cross-validation.
8. 📈 **Model Evaluation** - Evaluate models using multiple classification metrics.
9. 🔍 **Comparative Analysis** - Compare the predictive performance of the three algorithms.
10. 🌾 **Crop Recommendation** - Use the trained models to recommend suitable crops based on input conditions.

## 🤖 Machine Learning Models

### 🌳 Random Forest

An ensemble classification algorithm that combines multiple decision trees to improve prediction accuracy and robustness.

### 📊 Naive Bayes

A probabilistic classification algorithm based on Bayes' theorem and the assumption of conditional independence between features.

### 📍 K-Nearest Neighbors

A distance-based classification algorithm that predicts the class of a sample based on its nearest training instances.

## 📈 Evaluation Metrics

The models are evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Cross-Validation Score**

## 🏆 Comparative Results

| Model                   | Test Accuracy |
| ----------------------- | ------------: |
| **Naive Bayes**         |    **99.55%** |
| **Random Forest**       |    **99.32%** |
| **K-Nearest Neighbors** |    **95.68%** |

Based on the experimental results, **Naive Bayes achieved the highest test accuracy**, followed by Random Forest and K-Nearest Neighbors.

## 🔧 Hyperparameter Optimization

The research also investigates model optimization using:

* Grid Search
* Random Search
* 5-Fold Cross-Validation

## 🛠️ Technologies & Tools

* **Programming Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Visualization:** Matplotlib, Seaborn
* **Code Editor:** Google Colab

## 🎯 Research Objective

The primary objective of this research is to **comparatively analyze machine learning classification algorithms for crop recommendation** and identify an effective model for predicting suitable crops from soil and climatic conditions.

## 🔮 Future Research

* 🌾 Evaluation using larger and more diverse agricultural datasets
* 🛰️ Integration of satellite and remote-sensing data
* 🤖 Investigation of additional machine learning and deep learning models
* 🌦️ Incorporation of real-time weather and soil measurements

## 📚 Research Paper

This repository contains the implementation, experiments, and analysis associated with the research study:

**"Crop Recommendation Through Comparative Analysis of Machine Learning Algorithms"**

## 📧 Contact

For questions or feedback, please open an issue on GitHub.

---

⭐ If you found this research repository helpful, please consider giving it a star!
