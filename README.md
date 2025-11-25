# HeartDisease-ML
Heart-Disease-Prediction-ML/
│
├── data/
│   └── heart_data.csv 
│
├── notebooks/
│   └── heartdiseaseassign.ipynb
│
├── README.md

## Project Overview
Heart disease remains one of the leading causes of death globally. Early diagnosis through data-driven insights can save lives.  
This project builds a machine learning classification model to predict whether a person is likely to develop heart disease based on clinical data such as age, cholesterol levels, resting blood pressure, chest pain type, etc.

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding and scaling
- Model training & evaluation (Logistic Regression / others)
- Performance comparison

---

## Dataset Description
The dataset contains **11 clinical features** used to predict heart disease.

### **Attribute Information**  

- **Age** – Age of the patient (years)  
- **Sex** – M: Male, F: Female  
- **ChestPainType** – TA, ATA, NAP, ASY  
- **RestingBP** – Resting blood pressure (mmHg)  
- **Cholesterol** – Serum cholesterol (mg/dl)  
- **FastingBS** – Binary: 1 if fasting blood sugar > 120 mg/dl  
- **RestingECG** – ECG results: Normal/ST/LVH  
- **MaxHR** – Maximum heart rate (60–202)  
- **ExerciseAngina** – Y/N  
- **Oldpeak** – ST depression  
- **ST_Slope** – Up/Flat/Down  
- **HeartDisease** – Target variable (1 = disease, 0 = normal)

---

## Project Workflow
1. Load & inspect dataset
2. Detect missing data & anomalies
3. Encode categorical features (OneHotEncoder/LabelEncoding)
4. Scaling for numeric features (if required)
5. Train-Test split
6. Apply ML models
7. Evaluate performance using:
   - Accuracy
   - Confusion matrix
   - Precision, Recall, F1-score
   - ROC curve & AUC

---

## 🤖 Machine Learning Model Used
- **Logistic Regression** (Best baseline model)

> Logistic Regression is selected as the ideal model due to its strong performance and suitability for binary medical classification.

---

## Results Summary
| Metric | Score |
|--------|-------|
| Accuracy | ~81% (varies by train/test split) |
| Classification Report | Good balance of precision & recall |
| Confusion Matrix | Shows strong prediction for positive class |

---

## Technologies Used
| Technology | Purpose |
|-----------|---------|
| Python | Development |
| Pandas, NumPy | Data processing |
| Matplotlib, Seaborn | Visualization |
| Scikit-Learn | Machine learning |
| Jupyter Notebook | Development environment |
