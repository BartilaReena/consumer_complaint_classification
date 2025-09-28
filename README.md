# consumer_complaint_classification


This project demonstrates **multi-class text classification** using the
[Consumer Complaint Database] (https://catalog.data.gov/dataset/consumer-complaint-database).  
The goal is to classify consumer complaints into the following categories:

- 0 → Credit reporting, credit repair, or other  
- 1 → Debt collection  
- 2 → Consumer Loan  
- 3 → Mortgage  

---

 Steps Implemented

1. **Explanatory Data Analysis (EDA) & Feature Engineering**  
   - Inspect dataset  
   - Select relevant columns  
   - Map product categories to numeric labels  

2. **Text Pre-processing**  
   - Lowercasing  
   - Removing punctuation & special characters  
   - TF-IDF vectorization  

3. **Model Selection**  
   - Logistic Regression (default)  
   - Optionally compare Random Forest and SVM  

4. **Model Training & Evaluation**  
   - Train on TF-IDF features  
   - Evaluate with accuracy, classification report & confusion matrix  

5. **Prediction**  
   - Function predict_complaint() allows testing on new text  

---




