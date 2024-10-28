# Flight-Prediction
This project aims to predict disruptions (cancellations, diversions, or delays) for flights before takeoff using machine learning. 


Overview

This project focuses on predicting whether a flight will face a disruption—defined as cancellations, diversions, or delays—using historical flight data from the past five years, spanning the COVID-19 period. The goal is to enhance both logistical efficiency for airlines and informed decision-making for travelers by predicting disruptions based only on information available before takeoff.

Project Goal

The primary objective was to train a model to classify flights as likely disrupted or non-disrupted based on pre-flight information. The model can potentially save costs for airlines by optimizing schedules and improve customer experience by providing insights into possible delays or cancellations.

Approach

1. Data Selection and Preprocessing
Selected a medium-sized dataset, balancing model accuracy with processing efficiency.
Included only pre-takeoff variables (e.g., flight duration, origin airport, airline, date/time) to ensure predictions are based on real-time availability.
Split data into training and test sets to maintain unbiased evaluation.
2. Data Cleaning and Standardization
Cleaned and standardized the dataset to ensure consistency.
Performed exploratory visualizations, comparing disruption rates in training and test sets and analyzing the effect of COVID-19 on flight disruptions.
3. Pipeline Creation
Developed a preprocessing pipeline to standardize numerical data and encode categorical variables.
Streamlined data transformation to apply consistently across training and test sets.
4. Model Selection and Training
Trained three machine learning models: Logistic Regression, Decision Tree, and Random Forest.
Evaluated each model based on accuracy, particularly focusing on handling class imbalance (disruptions were less common).
Chose Random Forest for further fine-tuning due to its strong accuracy and generalizability.
5. Model Evaluation
Assessed models using ROC curves to compare true and false positive rates.
Fine-tuned the Random Forest model using grid search to enhance its performance across various datasets.
Results

The Random Forest model emerged as the best performer with an approximate accuracy of 78%, successfully predicting non-disruptions while improving accuracy for disruptions compared to other models. The final model demonstrated a robust capacity for real-world application and adaptability across new data scenarios.

Future Applications

This model could benefit:

Airlines: Enabling preemptive actions for better resource allocation and minimizing potential losses due to disruptions.
Travelers: Providing preemptive disruption alerts for better travel planning.

Notebook File: Contains the full analysis, model training, and evaluation steps.
PDF Report: Summarizes the project, methodology, and findings.
Conclusion

This project provides a solid foundation for real-time flight disruption prediction. With continued refinement, the model could help both airlines and travelers make informed decisions, enhancing efficiency and customer satisfaction across the industry.
