# Road Accident Severity Prediction

## Overview
This project focuses on predicting the severity of road accidents using Machine Learning techniques.  
Accurate severity prediction can help emergency response teams, traffic authorities, and policymakers
take faster and more informed decisions.

## Problem Statement
Road accidents are a major cause of fatalities worldwide.  
Manual analysis of accident severity is time-consuming and often reactive.  
This project aims to automatically predict accident severity levels based on driver behavior,
weather conditions, and road-related features.

## Dataset
The dataset contains structured data with features such as:
- Weather conditions
- Road type
- Time of accident
- Driver-related attributes
- Vehicle-related information

Data preprocessing included:
- Handling missing values
- Encoding categorical features
- Feature scaling where required

## Methodology
1. Performed exploratory data analysis (EDA)
2. Preprocessed the dataset for model training
3. Implemented a **Decision Tree Classifier**
4. Split data into training and testing sets
5. Evaluated performance using accuracy and confusion matrix

## Model Used
- Decision Tree Classifier (Supervised Learning)

## Results
- Achieved approximately **91% accuracy**
- The model was able to identify important contributing features
  such as weather conditions and road type

## Tools & Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

## Key Learnings
- End-to-end ML pipeline development
- Feature importance analysis
- Model evaluation and interpretation
- Practical understanding of supervised learning

## Future Improvements
- Implement ensemble models like Random Forest and XGBoost
- Perform hyperparameter tuning
- Deploy the model as a web application
- Extend to real-time accident data
