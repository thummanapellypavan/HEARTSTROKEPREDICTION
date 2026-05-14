Automated Stroke Prediction Using Machine Learning
An Explainable and Exploratory Study With a Web Application for Early Intervention

Project Overview

Stroke is one of the leading causes of death worldwide and occurs when the blood supply to the brain is interrupted. Early detection and timely medical intervention can significantly reduce mortality and improve patient recovery.

This project presents an automated stroke prediction system using Machine Learning and Explainable AI (XAI) techniques. The system predicts whether a patient is likely to suffer from a stroke based on healthcare data and provides explainable insights into the most influential features affecting prediction.

The project also includes a user-friendly application for healthcare analysis, model training, visualization, and prediction.

Features

• Healthcare dataset preprocessing  
• Missing value handling  
• Imbalanced data handling using SMOTE  
• Feature selection using CHI-Square (CHI2)  
• Training multiple Machine Learning algorithms  
• Explainable AI using SHAP  
• Performance comparison graph  
• Stroke prediction from test data  
• Interactive application interface  

Machine Learning Algorithms Used

• Random Forest  
• Logistic Regression  
• Support Vector Machine (SVM)  
• K-Nearest Neighbors (KNN)  
• Naive Bayes  
• XGBoost  
• CatBoost  

Model Performance

Random Forest — 95% Accuracy  
Logistic Regression — 78% Accuracy  
SVM — 81% Accuracy  
KNN — 91% Accuracy  
Naive Bayes — 77% Accuracy  
XGBoost — 89% Accuracy  
CatBoost — 95% Accuracy  

Explainable AI (XAI)

This project uses SHAP (SHapley Additive exPlanations) to identify the most important features influencing stroke prediction.

Important features include:

• Age  
• Smoking Status  
• BMI  
• Hypertension  
• Heart Disease  
• Glucose Level  

These explainable insights help doctors prioritize critical medical factors for faster diagnosis and treatment.

Dataset

Dataset used:
Stroke Prediction Dataset from Kaggle

The dataset contains healthcare information such as:

• Age  
• Gender  
• Hypertension  
• Heart Disease  
• BMI  
• Smoking Status  
• Glucose Level  
• Stroke Label  

Technologies Used

• Python  
• Scikit-learn  
• XGBoost  
• CatBoost  
• Pandas  
• NumPy  
• Matplotlib  
• Seaborn  
• SHAP  

Data Preprocessing Techniques

• Missing value removal  
• Label encoding for categorical values  
• Data normalization  
• SMOTE for balancing data  
• CHI2 feature selection  
• Train-test splitting (80% Training / 20% Testing)  

Application Workflow

Step 1: Upload Dataset  
Upload the healthcare stroke dataset into the application.

Step 2: Data Visualization  
The system displays graphs for normal and stroke patient distribution.

Step 3: Preprocessing  
The dataset is cleaned and split into training and testing data.

Step 4: Train Machine Learning Models  
Users can train different algorithms and evaluate their performance.

Step 5: Compare Algorithms  
Comparison graphs are generated using:
• Accuracy  
• Precision  
• Recall  
• F1-Score  

Step 6: Predict Stroke  
Upload test data to predict whether the patient is:
• Stroke  
• Normal  

How to Run the Project

Step 1:

```bash
git clone https://github.com/thummanapellypavan/HEARTSTROKEPREDICTION.git
```

Step 2:

```bash
cd HEARTSTROKEPREDICTION
```

Step 3:

```bash
pip install -r requirements.txt
```

Step 4:

Run the application using:

```bash
python main.py
```

OR double click:

```text
run.bat
```

Future Enhancements

• Deep Learning implementation  
• Cloud deployment  
• Mobile application support  
• Advanced healthcare analytics dashboard  

Conclusion

This project demonstrates how Machine Learning and Explainable AI can assist in early stroke prediction and medical decision-making. Among all implemented algorithms, Random Forest and CatBoost achieved the highest prediction accuracy of 95%.

The integration of SHAP Explainable AI improves transparency and trust in prediction results, making the system more useful for healthcare professionals.

Author

Pavan Thummanapelly

Final Year Major Project  
Machine Learning and Healthcare Analytics
