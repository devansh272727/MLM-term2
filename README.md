# MLM Project 2: Supervised Learning Models on Import-Export Dataset

## Project Description
This project explores supervised learning models to analyze and classify data from an import-export dataset. It involves data preprocessing, exploratory data analysis, and the application of machine learning models for classification and insights generation.

## Contents
1. Project Information
2. Dataset Overview
3. Objectives
4. Methodology
5. Results and Insights
6. Tools and Technologies
7. How to Run the Project
8. Author

---

## 1. Project Information
- **Title**: Data Exploration with Python using Pandas & Numpy Libraries
- **Prepared By**: Devansh Pratap Singh (055037)

---

## 2. Dataset Overview
- **Data Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/chakilamvishwas/imports-exports-15000)
- **Sample Size**: 5001 entries (from an original 15,000 rows)
- **Key Features**:
  - `Transaction_ID`: Unique identifier for trade transactions
  - `Country`: Country of origin/destination
  - `Product`: Traded product details
  - `Value`, `Weight`, and `Quantity`: Quantitative measures
  - `Shipping_Method`, `Port`, and `Customs_Code`: Logistical data
  - More features such as `Supplier`, `Customer`, `Invoice_Number`

---

## 3. Objectives
- Classify the dataset into meaningful categories using supervised learning models.
- Identify key features and their thresholds for effective classification.
- Determine the best classification model using performance metrics.

---

## 4. Methodology
### Data Preprocessing
- **Encoding**: Ordinal encoding for categorical variables.
- **Scaling**: Min-Max scaling for numerical variables.
- **Splitting**: Training and testing split (70:30).

### Machine Learning Models
- Logistic Regression
- Support Vector Machines (SVM)
- Decision Trees
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Ensemble methods (Bagging and Boosting)

### Evaluation Metrics
- Confusion Matrix
- Accuracy, Precision, Recall, F1-Score
- Area Under Curve (AUC)
- K-Fold Cross-Validation

---

## 5. Results and Insights
- **Top Performing Model**: SVM with the highest test accuracy (0.3738).
- **Key Features Identified**: Country, Product, Value, Weight, and Customs_Code.
- **Recommendations**:
  - Address class imbalance with sampling techniques.
  - Leverage Random Forest for larger datasets despite computational costs.

---

## 6. Tools and Technologies
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels
- **Visualization**: Heatmaps, Correlation Matrices, Histograms, Subplots
- **Development Environment**: Jupyter Notebook

---

## 7. How to Run the Project
1. Clone the repository or download the `.ipynb` file.
2. Ensure Python 3.x and all required libraries are installed.
3. Open the notebook in Jupyter or Google Colab.
4. Follow the instructions to load the dataset and execute the cells sequentially.

---

## 8. Author
**Devansh Pratap Singh**  

