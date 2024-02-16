# Covid_data_Prediction
This project provides the data based on classification to check if the patient is covid +ve or -ve. 

# Steps for Performing the Task:
1. Importing Necessary Libraries
2. Data Pre-Processing and Data Cleaning
3. Label Encoder (For Converting Categorical Data into Numerical)
4. Creating X and Y for Training Data
5. Performed Standard Scalar (To bring the data in the unifrom range)
6. Splitting the data into Training and Validation Testing
7. Building Logistic Regression Model
8. Generate Classifcation report (Accuracy -> 0.66)
9. Tuned Logistic regresison Model (**Adjustment of Threshold - 0.456**, **Accuarcy - 0.72**, **Recall for class 0 - 0.70**, **Recall for class 1 - 0.74**)
10. Building Decision Tree Model (**Accuracy - 0.80**, **Recall for class 0 - 0.82**, **Recall for class 1 - 0.79**)

# Conclusion
**Logistic Regression**, Decision Tree is performed much better as we can see that the **Recall** & **f1-score** is **Higher** than **Logistic Regression**
