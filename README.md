Heart Disease Prediction
This project uses machine learning to predict the presence of heart disease in patients based on medical factors.

Overview
The model uses the Heart Disease UCI dataset to classify whether a patient has heart disease (1) or not (0). The dataset contains various medical attributes such as age, gender, cholesterol levels, blood pressure, etc. The logistic regression algorithm is used for classification.

Features
Age: Age of the patient
Sex: Gender (0 = male, 1 = female)
cp: Chest pain type
trestbps: Resting blood pressure
chol: Serum cholesterol
fbs: Fasting blood sugar (> 120 mg/dl)
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise induced angina
oldpeak: Depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment
ca: Number of major vessels colored by fluoroscopy
thal: Thalassemia (0 = normal, 1 = fixed defect, 2 = reversible defect)
target: 0 = No heart disease, 1 = Heart disease (target variable)

Technologies Used
Python
Scikit-learn: For building and training the logistic regression model
Pandas: For data manipulation
Tkinter: For the graphical user interface (GUI) to upload CSV file
