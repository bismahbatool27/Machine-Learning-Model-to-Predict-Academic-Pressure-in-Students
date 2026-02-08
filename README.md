# Academic Stress Prediction Using Machine Learning

## 📌 Project Overview
This project uses a Decision Tree Classifier to predict whether a student experiences high academic pressure based on demographic and lifestyle factors such as age, gender, education level, and sleep duration.  
The goal is to demonstrate basic machine learning workflow including data preprocessing, feature encoding, model training, and prediction.

---

## 📊 Dataset Description
The dataset is based on student survey responses. The following features were used:

- **Age Group** – Converted into numeric values by averaging the age range  
- **Gender** – Encoded numerically (Female = 0, Male = 1)  
- **Education Level** – Encoded as College, University, or Other  
- **Sleep Time** – Converted into average hours of sleep per night  
- **Target Variable: Academic Pressure**  
  - `0` = Low Academic Pressure  
  - `1` = High Academic Pressure  

---

## ⚙️ Methodology
The following steps were performed:

1. Data cleaning and column renaming  
2. Conversion of categorical data into numeric format  
3. Feature engineering for age and sleep duration  
4. Train-test split of the dataset  
5. Training a Decision Tree Classifier  
6. Making predictions on unseen data  

---

## 📈 Model Used
**Decision Tree Classifier**

**Why this model?**
- Easy to understand and interpret  
- Suitable for beginners  
- Works well with small datasets  

---

## ✅ Results
- The model predicts whether a student experiences high academic pressure.
- Output interpretation:
  - `0` → Low Academic Pressure  
  - `1` → High Academic Pressure  


