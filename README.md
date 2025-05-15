# 🍷 Wine Quality Insights with Orange Data Mining

This project leverages [Orange Data Mining](https://orangedatamining.com/) to analyze and visualize the **Wine Quality dataset**. The goal is to gain insights into the factors that affect wine quality and to build predictive models using visual programming with Orange.

---

## 📁 Project Structure

- `f1.ows` – Workflow 1: Data exploration, preprocessing, and correlation analysis.
- `f2.ows` – Workflow 2: Machine learning models for predicting wine quality.

---

## 🧰 Tools & Technologies

- **Orange Data Mining** – Visual programming tool for data science.
- **Wine Quality Dataset** – Contains physicochemical test results and quality scores for red/white wines.

---

## 📊 Key Objectives

- Explore the distribution and relationship of features in the wine dataset.
- Identify key attributes that correlate with wine quality.
- Apply classification models like Random Forest, SVM, and Logistic Regression to predict quality.
- Evaluate model performance with metrics such as Accuracy, ROC, and Confusion Matrix.

---

## 📦 Dataset

The dataset used is the [Wine Quality dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) from the UCI Machine Learning Repository. It includes:

- 11 physicochemical attributes (e.g., alcohol, pH, sulphates)
- Quality scores (0–10 scale)

If not already bundled, you can download it from UCI or import it using Orange's built-in “Download Datasets” widget.

---

## 🔧 How to Use

1. **Install Orange**  
   Download and install Orange from [orangedatamining.com](https://orangedatamining.com/download/).

2. **Open Workflows**  
   Launch Orange and open:
   - `f1.ows` for exploratory data analysis
   - `f2.ows` for classification and predictive modeling

3. **Run the Workflows**  
   Click through each widget to visualize the pipeline and results. You can modify the workflows or test other models easily.

---

## 🔍 Workflow Highlights

### `f1.ows`: Exploratory Data Analysis
- **File**: Load wine dataset (CSV)
- **Select Columns**: Focus on target and predictor features
- **Box Plot & Scatter Plot**: Visualize data distribution and correlations
- **Correlation Heatmap**: Understand feature interactions
- **Data Table**: Explore raw and filtered data

### `f2.ows`: Classification Modeling
- **Preprocessing**: Normalize or discretize data
- **Modeling**: Test multiple algorithms (e.g., Random Forest, Naive Bayes)
- **Evaluation**: ROC, Confusion Matrix, and Cross Validation

---

## 📈 Sample Insights

- **Alcohol** and **volatile acidity** are among the most influential features.
- Higher alcohol content tends to be associated with better quality wines.
- Classification models achieve reasonable accuracy (~60–70%) in predicting wine quality.

---

## ✅ Requirements

- Orange 3.33+ (or latest version)
- Internet access (for optional dataset download)

---

## 📌 Notes

- The quality scores are often skewed (more average wines), so class balancing or binning may improve performance.
- You can extend this project with feature engineering or deep learning (via Python scripting).

---
