# Wine Classification – Supervised Learning Project

This project applies a full supervised machine learning flow on the **Wine Recognition dataset**. The goal is to classify wines into three cultivars based on 13 chemical features.

## 📑 Project Overview
- **Dataset**: Wine Recognition dataset (UCI) – 13 chemical features, 3 classes.  
- **Task**: Multi-class classification.  
- **Evaluation Metric**: Macro F1-score.  

## 🔄 Workflow
1. **Data Preparation & EDA**  
   - Checked class distribution, feature correlations, and plotted feature boxplots.  
   - Used PCA to visualize class separation.  

2. **Experiments**  
   - Compared raw vs. standardized data.  
   - Trained **Logistic Regression** and **Random Forest** with multiple hyperparameters.  
   - Used **GridSearchCV with Stratified 5-Fold CV** to find the best setup.  

3. **Final Training**  
   - Re-trained the best model (Logistic Regression + StandardScaler, `C=0.1`, `solver=lbfgs`) on the full training set.  

4. **Test Evaluation**  
   - Evaluated on the held-out test set.  
   - Reported **100% Accuracy and 100% Macro F1-score**.  
   - Displayed the first 5 predictions and confusion matrix.  

## ✅ Results
- **Best Model**: Logistic Regression (with StandardScaler)  
- **Test Accuracy**: 100%  
- **Test Macro F1-score**: 100%  

## 📂 Repository Structure
