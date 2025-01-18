# heart-disease-analysis
Exploratory Data Analysis of heart disease data

## Project Overview:
This project performs an exploratory data analysis (EDA) on a heart disease dataset to identify key risk factors contributing to heart disease. The dataset is sourced from Kaggle and contains various health metrics and demographics that help in understanding heart disease risk.

### Dataset Source:
- **Kaggle Dataset:** [Heart Disease Data](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)

---

## Dataset Summary:
- **Total Rows:** 303
- **Total Columns:** 14

### Key Columns:
- **age**: Age of the patient. (Integer type)
- **sex**: Gender of the patient (1 = male, 0 = female). (Integer type)
- **cp**: Chest pain type. (Categorical)
- **trestbps**: Resting blood pressure. (Integer type)
- **chol**: Serum cholesterol. (Integer type)
- **fbs**: Fasting blood sugar. (Binary)
- **restecg**: Resting electrocardiographic results. (Categorical)
- **thalach**: Maximum heart rate achieved. (Integer type)
- **exang**: Exercise induced angina. (Binary)
- **oldpeak**: Depression induced by exercise. (Float type)
- **slope**: Slope of peak exercise ST segment. (Categorical)
- **ca**: Number of major vessels colored by fluoroscopy. (Integer type)
- **thal**: Thalassemia. (Categorical)
- **num**: Presence of heart disease (1 = Yes, 0 = No). (Integer type)

---

## Data Quality:
- **Missing Values:**There are 10 columns in dataset that have missing values
- Columns with missing values: ['trestbps', 'chol', 'fbs', 'restecg', 'thalch', 'exang', 'oldpeak', 'slope', 'ca', 'thal']

---

## Analysis Insights:
- **Age Distribution**: Visualized the distribution of patients across different age groups.
- **Cholesterol Levels**: Comparison of cholesterol levels for patients with and without heart disease.
- **Blood Pressure**: Analyzed resting blood pressure levels and their correlation with heart disease.
- **Heart Rate**: Explored the maximum heart rate achieved and its impact on heart disease.

### Key Risk Indicators:
- **Cholesterol Levels**: Higher cholesterol levels are associated with a higher likelihood of heart disease.
- **Age & Gender**: Age and gender are significant predictors of heart disease risk.
- **Resting Blood Pressure**: Elevated blood pressure levels are strongly linked to heart disease.

---

## Statistical Summary for Key Features:
- **Age**:
  - **Minimum:** 28
  - **Maximum:** 77
  - **Mean:** 53.51
  - **Median:** 54
- **Cholesterol**:
  - **Minimum:** 0
  - **Maximum:** 603
  - **Mean:** 132
  - **Median:** 223
- **Resting Blood Pressure**:
  - **Minimum:** 0
  - **Maximum:** 200
  - **Mean:** 132.6
  - **Median:** 130

---

## Visualizations:
- **Cholesterol Levels vs. Heart Disease**: A boxplot was used to visualize the differences in cholesterol levels between patients with and without heart disease.
- **Age Distribution**: A histogram was used to visualize the age distribution of patients in the dataset.
- **Outlier Detection**: Identified significant outliers in cholesterol and blood pressure data using boxplots.

---

## How to Run the Code

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hassan-069/heart-disease-analysis.git
