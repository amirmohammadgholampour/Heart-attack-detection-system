# Heart Disease Prediction

This project predicts the **likelihood of heart disease** in patients based on medical attributes.  
The dataset (`heart_dataset.csv`) contains various clinical features such as age, cholesterol level, blood pressure, and more.  

The goal is to classify patients into:
- **0 → Low chance of heart disease**  
- **1 → High chance of heart disease**

---

## 📊 Dataset Description

The dataset consists of medical records with the following attributes:

| Feature      | Description |
|--------------|-------------|
| **age**      | Age of the patient |
| **sex**      | Gender (1 = Male, 0 = Female) |
| **cp**       | Chest pain type:<br>1 = Typical angina<br>2 = Atypical angina<br>3 = Non-anginal pain<br>4 = Asymptomatic |
| **trtbps**   | Resting blood pressure (mm Hg) |
| **chol**     | Serum cholesterol level (mg/dl) |
| **fbs**      | Fasting blood sugar (1 = Yes, 0 = No) |
| **restecg**  | Resting electrocardiographic results:<br>0 = Normal<br>1 = ST-T wave abnormality<br>2 = Left ventricular hypertrophy |
| **thalachh** | Maximum heart rate achieved |
| **exng**     | Exercise induced angina (1 = Yes, 0 = No) |
| **oldpeak**  | ST depression induced by exercise |
| **slp**      | Slope of the peak exercise ST segment |
| **caa**      | Number of major vessels (0–3) |
| **thall**    | Thalassemia (0 = Normal, 1 = Fixed defect, 2 = Reversible defect) |
| **target**   | Target variable:<br>0 = Low chance of heart disease<br>1 = High chance of heart disease |

---

### Machine Learning algorithms: 
SVM, Logistic Regression, RandomForest, KNN, GradientBoosting