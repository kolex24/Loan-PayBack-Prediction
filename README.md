# Loan-PayBack-Prediction
This project focuses on predicting loan payback probability for a financial lending dataset. The objective is to determine whether a borrower will successfully payback their loan or default. This type of predictive system is crucial for banks, microfinance institutions, and fintech lenders, as it helps reduce risk, and optimize lending decisions.
## Project Objectives
1. **Build a complete loan default prediction pipeline**
   - Load, clean, and preprocess the raw loan dataset
   - Handle inconsistent values, missing records
   - Encode categorical features using **Target Encoding**

2. **Address strong class imbalance**
   - Compute scale_pos_weight
   - Split the dayaset into train and test
   - Track metrics such as AUC, recall, precision

3. **Engineer meaningful financial feature**
   - Annual income bracket
   - Credit score bracket
   - Annual debt payment
   - Monthly debt payment
   - Monthly Income
   - Total debt burden
   -  Subgrade
   -  Grade
  
4. **Train optimized gradient boosting models**
   - Implement LGBMClassifiers, XGBClassifier and CatBoostClassifier
   - Apply tuned hyperparameters for each model
   - Monitor performance using AUC on test (validation) set
   - use early stopping for and callbacks for efficient training
