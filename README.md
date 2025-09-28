
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

 Screenshots


 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/57f0585b-6643-4a3b-aa28-5465b5a12e98" />



<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/2f697f1e-8f70-4084-96e8-8f4f1c49163e" />



<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/aaecc240-6441-4fc0-98b9-be8f5df5d46c" />



<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/c1a65975-be74-4c91-be25-02d583f535a5" />

