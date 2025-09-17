# ❤️ Heart Disease Prediction using Machine Learning

## Project Overview
This project predicts the likelihood of heart disease in a patient based on health parameters such as age, blood pressure, cholesterol, and more.  
It uses **Logistic Regression** (a classification algorithm) to train a machine learning model and evaluate its performance.  

The project demonstrates:
- Data preprocessing  
- Exploratory Data Analysis (EDA) with visualizations  
- Model training and testing  
- Model evaluation with accuracy, confusion matrix, and classification report  


## Dataset
The dataset for this project was taken from **Kaggle**:  
👉 [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)  

- Rows: **304 patients**  
- Features: **14 health attributes**  
- Target: Presence (1) or Absence (0) of heart disease  

### Feature Information
| Feature   | Description |
|-----------|-------------|
| age       | Age of the patient |
| sex       | Gender (1 = male, 0 = female) |
| cp        | Chest pain type (0–3) |
| trestbps  | Resting blood pressure (mm Hg) |
| chol      | Serum cholesterol (mg/dl) |
| fbs       | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| restecg   | Resting electrocardiographic results (0–2) |
| thalach   | Maximum heart rate achieved |
| exang     | Exercise induced angina (1 = yes, 0 = no) |
| oldpeak   | Depression induced by exercise relative to rest |
| slope     | Slope of the peak exercise ST segment |
| ca        | Number of major vessels (0–3) colored by fluoroscopy |
| thal      | Thalassemia (0 = normal, 1 = fixed defect, 2 = reversible defect) |
| target    | 1 = Heart disease present, 0 = No heart disease |


## Technologies Used
- Python  
- Pandas, NumPy (data processing)  
- Matplotlib, Seaborn (visualizations)  
- Scikit-learn (ML model & evaluation)  
- Jupyter Notebook  


## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/moulyajagarlamudi/Heart_Disease_Prediction.git
   cd Heart_Disease_Prediction
