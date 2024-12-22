# TO GRANT OR NOT TO GRANT: DECIDING ON COMPENSATION BENEFITS
# Group 14

## Project Overview  
The New York Workers’ Compensation Board (WCB) plays a crucial role in regulating and adjudicating claims related to workplace injuries, volunteer workers, and other compensation cases. Since 2000, the WCB has handled over 5 million claims, making manual claim reviews an increasingly time-consuming and complex process.  

To address this challenge, Nova IMS partnered with the WCB to develop a machine learning solution aimed at automating decision-making for new claims. This project focuses on building, evaluating, and optimizing classification models to predict the type of injury (Claim Injury Type) associated with a claim, enhancing the efficiency and accuracy of the WCB's operations.  

## Project Goals  
1. **Multiclass Classification Benchmarking**  
   - Develop a classification model to accurately predict the injury type for claims based on historical data.  
   - Use claims data from 2020 to 2022 to train, validate, and test models.  
   - Establish a robust model assessment strategy to compare multiple candidate models and identify the most generalizable solution.  

2. **Model Optimization**  
   - Explore strategies such as hyperparameter tuning, feature selection, and pre-processing adjustments to enhance model performance.  
   - Compare optimized models against initial benchmarks and document findings.  

3. **Additional Insights**  
   - Develop an analytics interface that provides predictions for new claim inputs.  
   - Explore predicting "Agreement Reached" and examine the potential to improve model performance.  

## Dataset Details  
This project leverages two datasets provided by the WCB:  

1. **Training Dataset**  
   - Contains claims data from January 2020 to December 2022.  
   - Used to train and validate machine learning models.  

2. **Test Dataset**  
   - Contains claims data from January 2023 onward.  
   - Used to predict the Claim Injury Type, with model performance evaluated through a Kaggle competition.  

### Evaluation through Kaggle  
The test dataset's predictions will be submitted to a Kaggle competition, where performance metrics will determine the model's effectiveness. This setup provides a real-world benchmarking environment to assess the generalizability of the developed models.

## Methodology  
### 1. Data Preprocessing  
- Handling missing data and outliers.  
- Feature engineering and selection to enhance model interpretability and performance.  

### 2. Model Development  
- Implementing multiple classification algorithms (e.g., Decision Trees, Random Forest, Gradient Boosting, Neural Networks).  
- Evaluating models using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.  

### 3. Model Optimization  
- Hyperparameter tuning using grid search.  
- Comparing optimized models to initial benchmarks.  

### 4. Insights and Advanced Analytics  
- Performing feature importance analysis to understand key factors driving predictions.
