📊 Student Performance Analysis & Prediction
🚀 Project Overview

This project analyzes student academic performance and predicts outcomes using machine learning techniques. It focuses on understanding how factors like study hours, attendance, and class participation influence student success.

🎯 Objectives
Analyze student performance data
Visualize patterns and relationships
Build multiple machine learning models
Compare model performance
Predict grades (multi-class) and pass/fail (binary)
📁 Dataset
~100,000 student records
Features:
weekly_self_study_hours
attendance_percentage
class_participation
grade
Data preprocessing included:
Removing irrelevant columns (student_id, total_score)
Handling missing values
Encoding categorical variables
📊 Exploratory Data Analysis (EDA)
Grade distribution analysis
Histograms for feature distribution
Box plots for outlier detection
Correlation heatmap
Relationship between study hours and grades
🤖 Machine Learning Models

The following models were implemented and compared:

Logistic Regression
Decision Tree
Random Forest
Gradient Boosting ✅ (Best Model)
XGBoost
📈 Model Performance
Model	Accuracy	F1 Score
Logistic Regression	0.6957	0.6860
Decision Tree	0.6058	0.6068
Random Forest	0.6620	0.6558
Gradient Boosting	0.6959	0.6878
XGBoost	0.6943	0.6866
✅ Pass/Fail Prediction
Model Used: XGBoost
Accuracy Achieved: 95.63%

📌 Binary classification performs better due to reduced complexity compared to multi-class grade prediction.

🔍 Evaluation Metrics
Accuracy
F1 Score
Confusion Matrix
Cross-Validation (5-fold)
🔄 Cross-Validation
Mean Accuracy: ~69.46%
Ensures model stability and reliability
📌 Key Insights
Study hours and attendance strongly influence performance
Boosting models perform best for complex data
Class imbalance affects prediction of higher grades
🛠️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost
🚀 Future Improvements
Use larger real-world datasets
Apply deep learning models
Handle class imbalance (SMOTE, weighting)
Improve model accuracy
Deploy using Streamlit
📌 Conclusion

This project demonstrates that student performance can be effectively predicted using machine learning techniques. Ensemble models like Gradient Boosting and XGBoost provide the best results, while binary classification achieves higher accuracy compared to multi-class prediction.

👨‍💻 Author

Adhvai
