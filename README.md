
# Cardiovascular Diseases Risk Prediction

Heart disease is a major global health concern. This project aims to leverage data science and machine learning techniques to predict the risk of cardiovascular diseases based on various attributes such as exercise habits, diet, medical history, and lifestyle factors. By improving early detection and providing actionable insights, this project strives to enhance healthcare outcomes.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
4. [Models and Techniques Used](#models-and-techniques-used)
5. [Results](#results)
6. [Getting Started](#getting-started)
7. [How to Contribute](#how-to-contribute)
8. [License](#license)

---

## Introduction
This project explores the prediction of cardiovascular disease risk using a dataset of health-related attributes. By analyzing risk factors such as BMI, exercise habits, smoking history, and dietary patterns, we aim to develop predictive models and provide interpretability for actionable insights.

---

## Dataset
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/alphiree/cardiovascular-diseases-risk-prediction-dataset). It contains 308,774 rows and 19 attributes, including:
- General health
- Checkup frequency
- Exercise habits
- Medical history (diabetes, skin cancer, etc.)
- BMI, height, and weight
- Dietary habits

### Data Preprocessing
- Removed duplicates (80 rows).
- Encoded categorical data (e.g., yes/no replaced with 1/0).
- Applied outlier detection and removal using the IQR method.
- Balanced the dataset using SMOTE for minority oversampling.

---

## Project Workflow
The project follows this structured workflow:
1. **Dataset Exploration**: Univariate, bivariate, and correlation analysis.
2. **Data Preprocessing**: Cleaning, feature encoding, outlier handling, and oversampling.
3. **Feature Engineering**: Identified important features for heart disease prediction.
4. **Model Development**:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - Artificial Neural Network
5. **Evaluation**: Performance metrics (accuracy, AUC-ROC) and model interpretability.

---

## Models and Techniques Used
1. **Baseline Model**: Logistic Regression
   - Accuracy: 82%
   - Key Insights: Transparent and interpretable coefficients.

2. **Decision Tree Classifier**
   - Accuracy: 88%
   - Advantages: Non-linear relationships and feature importance.

3. **Random Forest Classifier**
   - Accuracy: 93%
   - Advantages: Reduced overfitting and robust performance.

4. **Artificial Neural Network**
   - Accuracy: 83%
   - Advantages: Handles complex relationships and latent patterns.

### Key Visualizations
- Correlation heatmaps
- Top 10 features by importance
- AUC-ROC curves
- Distribution plots for key variables like exercise, BMI, and smoking history

---

## Results
- **Best Performing Model**: Random Forest Classifier with an accuracy of 93%.
- **Interpretability**: Decision Tree and Logistic Regression provided clear insights into key risk factors.
- **Key Risk Factors Identified**:
  - Age
  - Diabetes
  - Smoking history
  - BMI
  - Exercise habits

---

## Getting Started
### Prerequisites
- Python 3.7 or later
- Required libraries: `pandas`, `numpy`, `sklearn`, `seaborn`, `matplotlib`, `plotly`, `imblearn`, `tensorflow`, `sqlalchemy`, `pandasql`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cvd-risk-prediction.git
   cd cvd-risk-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the project:
   ```bash
   python main.py
   ```

---

## How to Contribute
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this template based on your specific project requirements or to include additional sections, such as "Challenges Faced" or "Future Work."
