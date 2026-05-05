# Student Performance Prediction System  

## 1. Overview  
This project focuses on predicting student academic performance using Machine Learning techniques. It analyzes key factors such as study hours, attendance, and previous marks to determine whether a student is likely to pass or fail. The project includes a complete pipeline from data preprocessing and exploratory analysis to model training, evaluation, and real-time prediction.

---

## 2. Objective  
- Predict student performance (Pass/Fail)  
- Identify at-risk students  
- Assist institutions in early intervention  
- Improve student academic outcomes  

---

## 3. Dataset  
The dataset contains 60 student records with the following features:  

- Study_Hours  
- Attendance  
- Previous_Marks  
- Assignments  
- Internal_Marks  

Target Variable:  
- Pass → 1  
- Fail → 0  

---

## 4. Technologies Used  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Google Colab / Jupyter Notebook  

---

## 5. Project Workflow  

### 5.1 Data Loading & Preprocessing  
- Loaded dataset using CSV upload  
- Checked dataset shape and missing values  
- Verified class distribution  
- Encoded target variable using LabelEncoder (Fail=0, Pass=1)  

### 5.2 Exploratory Data Analysis (EDA)  
- Study Hours vs Result distribution  
- Attendance vs Result (boxplot)  
- Previous Marks vs Internal Marks (scatter plot)  
- Pass vs Fail count visualization  
- Correlation heatmap to identify feature importance  

### 5.3 Feature Selection & Data Splitting  
- Selected features: Study_Hours, Attendance, Previous_Marks, Assignments, Internal_Marks  
- Split dataset into:  
  - 80% Training data  
  - 20% Testing data (Stratified split)  

### 5.4 Model Training  
Trained multiple classification models:  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Naive Bayes  

### 5.5 Model Evaluation  
- Accuracy  
- Precision  
- Recall  
- F1-Score  

**Model Performance:**  
All models achieved **100% accuracy** on the test dataset.  

**Best Model:** Logistic Regression (selected automatically based on accuracy)

---

## 6. Model Evaluation Plots  
- Model Accuracy Comparison Bar Chart  
- Confusion Matrix for best model  
- Feature correlation heatmap  
- EDA visualizations (histograms, boxplots, scatter plots)  

---

## 7. Key Features  
- Study Hours  
- Attendance  
- Previous Marks  
- Assignments  
- Internal Marks  

These features strongly influence student performance prediction.

---

## 8. Output  

### 8.1 Prediction on New Students  
- Predicts Pass/Fail  
- Displays probability (confidence score)  
- Identifies At-Risk students  

### 8.2 Manual Input Prediction  
- User enters student details  
- System predicts result with probability  
- Provides performance feedback and improvement suggestions  

### 8.3 At-Risk Student Detection  
- Predicts results for entire dataset  
- Filters students predicted to fail  
- Displays list of at-risk students  

---

## 9. Results Summary  

| Module | Description |
|--------|------------|
| Data Collection | 60 student records with 5 features |
| Preprocessing | Label encoding, null check, 80/20 split |
| EDA | Distribution, boxplots, scatter plots, heatmap |
| Models Trained | Logistic Regression, Decision Tree, Random Forest, Naive Bayes |
| Best Model | Logistic Regression |
| Output | Pass/Fail prediction and At-risk student identification |

---

## 10. How to Run  
1. Open Google Colab or Jupyter Notebook  
2. Upload the dataset file  
3. Run all cells step-by-step  
4. Enter new student data for predictions  

---

## 11. Conclusion  
This project demonstrates how machine learning can be used to predict student performance with high accuracy. It enables early identification of at-risk students and provides actionable insights for improving academic outcomes.

---

## 12. Future Enhancements  
- Integration with a mobile app for real-time alerts  
- Personalized AI-based learning recommendations  
- Integration with Learning Management Systems (LMS)  

 