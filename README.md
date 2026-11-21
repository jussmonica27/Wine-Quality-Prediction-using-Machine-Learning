# Wine-Quality-Prediction-using-Machine-Learning
A Machine Learning project that focuses on predicting Red Wine Quality using Python. It includes data preprocessing, exploratory data analysis (EDA), data visualization, outlier treatment, feature selection, and machine learning model development to analyze and predict wine quality based on its physicochemical properties.
# 🍷 Wine Quality Prediction using Machine Learning

 Project Overview
This project focuses on predicting Red Wine Quality using Machine Learning techniques. It analyzes the physicochemical properties of red wine to understand their relationship with wine quality and build classification models.

 Objectives
- Analyze the Red Wine Quality dataset.
- Perform data cleaning and preprocessing.
- Handle duplicate values and outliers.
- Perform Exploratory Data Analysis (EDA).
- Visualize different features and their relationship with wine quality.
- Apply feature selection techniques.
- Train and evaluate Machine Learning models.

 ataset
The project uses the **Red Wine Quality Dataset**, which contains physicochemical properties of red wine.

Some important features include:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target Variable)

Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Project Workflow

1. **Data Loading** – Importing the Red Wine Quality dataset.
2. **Data Understanding** – Checking dataset shape, columns, data types, and statistical information.
3. **Data Cleaning** – Checking missing values and removing duplicate records.
4. **Outlier Treatment** – Detecting and treating outliers using the IQR method.
5. **Exploratory Data Analysis** – Analyzing the distribution and relationships between features.
6. **Data Visualization** – Creating count plots, bar graphs, histograms, and correlation heatmaps.
7. **Feature Selection** – Applying SelectKBest with ANOVA F-test.
8. **Data Splitting** – Dividing the dataset into training and testing sets.
9. **Feature Scaling** – Applying StandardScaler.
10. **Model Training and Evaluation** – Training and comparing different classification algorithms.

Visualizations
The project includes the following visualizations:

- Wine Quality Distribution
- Alcohol vs Wine Quality
- Volatile Acidity vs Wine Quality
- Alcohol Distribution
- Residual Sugar vs Wine Quality
- Correlation Heatmap

Machine Learning Algorithms
The following classification algorithms are used:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

📈 Model Evaluation
The models are evaluated using the following performance metrics:

- Accuracy
- Precision
- Recall
- F1-Score

Installation

Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

How to Run the Project

1. Clone this repository.
2. Open the project folder.
3. Install the required libraries.
4. Open the Jupyter Notebook.
5. Run the notebook cells step by step.

Conclusion
This project demonstrates how Machine Learning techniques can be used to analyze and predict red wine quality based on its physicochemical properties. It also provides an understanding of data preprocessing, visualization, feature selection, and classification model evaluation.

Author
Monica S
