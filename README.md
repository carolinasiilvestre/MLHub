<p align="center">
  <img width="588" alt="ml_image" src="https://github.com/user-attachments/assets/000c04aa-6b1a-4fcf-89a9-5efb2ea9f6b9"/>
</p>

<h1 align="center">
  TO GRANT OR NOT TO GRANT: DECIDING ON COMPENSATION BENEFITS
</h1>

<h2 align="center">
  GROUP 14
</h2>

## Project Overview

This repository contains the work of a group project undertaken as part of the Master's program in Data Science and Advanced Analytics at Nova Information Management School (Nova IMS). The project aims to develop a machine learning model to assist the New York Workers' Compensation Board (WCB) in automating decision-making processes for workers’ compensation claims. With over 5 million claims under WCB's jurisdiction, our goal was to predict the "Claim Injury Type" using supervised learning techniques, ultimately achieving optimized model performance.

## Objectives

1. **Data Understanding and Preparation**:  
   - Perform exploratory data analysis to uncover key dataset characteristics.  
   - Handle missing values, outliers, and imbalances in the data.  
   - Engineer and select features for robust predictive modeling.

2. **Model Development and Comparison**:  
   - Train and evaluate multiple classification models, including KNN, Support Vector Classifier, Logistic Regression, Decision Trees, Random Forest, Neural Networks, and XGBoost.  
   - Identify the best-performing model and optimize its parameters for improved accuracy and reliability.  

3. **Open-Ended Exploration**:  
   - Analyze and predict the variable ‘Agreement Reached’ and assess its potential as an additional feature for enhancing primary model performance.

## Key Findings

- **Best Model**: XGBoost achieved the highest Kaggle score of 0.31619 for the prediction of "Claim Injury Type." 
- **Data Preprocessing**: Robust handling of skewed numerical variables, missing data, and encoding of high-cardinality categorical variables improved the model training process.  
- **Feature Selection**: Techniques like Lasso and Recursive Feature Selection were essential in mitigating dimensionality issues and computational complexity.  
- **Open-Ended Analysis**: Predicting ‘Agreement Reached’ with an AUC of 0.8732 using Support Vector Classifier (SVC) demonstrated the potential to enhance the primary prediction model, though improvements depended on the correlation of added features.  

## Repository Structure

- **Notebooks**:  
  - Exploratory Data Analysis  
  - Data Preprocessing  
  - Feature Engineering and Selection  
  - Model Training and Evaluation  
  - Open-Ended Analysis for ‘Agreement Reached’  
- **Reports**: Comprehensive documentation of the methodology, findings, and conclusions.

## Limitations and Future Work

### Limitations:
- High dimensionality and imbalanced target classes increased computational demands and risks of overfitting.
- Dependence on dataset quality limited potential for external validations.

### Future Work:
- Address target class imbalances using techniques like SMOTE (Synthetic Minority Oversampling Technique).  
- Explore ensemble methods (e.g., stacking or blending) to combine model strengths.  
- Incorporate external data sources such as economic and geographic indicators to enrich feature space.  

## Conclusion

This project demonstrates the effectiveness of machine learning in automating complex decision-making processes in the insurance sector. While the findings align with our expectations, identified limitations and opportunities for improvement point toward the potential for more advanced analyses in the future.
