🩺 Diabetes Prediction using Logistic Regression

This project is a **Machine Learning model** that predicts whether a person is diabetic or not based on health metrics like glucose level, BMI, insulin, etc.  
It uses the **Pima Indians Diabetes Dataset** and implements a Logistic Regression classifier in Python.

📌 Dataset Source

The dataset is publicly available from [Plotly Datasets](https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv), originally from the **UCI Machine Learning Repository**.

 📊 Features Used

- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age

Target Column:
- **Outcome** → 0 (Non-Diabetic), 1 (Diabetic)

🧹 Data Cleaning

Some columns had invalid zero values (like zero glucose or BMI). These were handled by replacing 0s with the **mean of that column**:

**Models used**
Algorithm: Logistic Regression
Train-Test Split: 80-20
Max Iterations: 1000

**Model Accuracy**
Accuracy: ~76.6%

**Evaluation Metrics:**
- Precision
- Recall
- F1-Score
- Confusion Matrix
  
**Confusion Matrix**

<img width="501" height="393" alt="image" src="https://github.com/user-attachments/assets/eaeb910e-1e7e-483b-bc8a-2f72ee0f6626" />

**Output**

<img width="1739" height="480" alt="Screenshot 2025-07-31 094220" src="https://github.com/user-attachments/assets/a3aedfae-ea94-4782-bd6f-f741b043f9ca" />

