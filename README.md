# Mushroom Classification: Edible vs. Poisonous

## Description:
This project aims to classify mushrooms into edible or poisonous categories based on various features such as cap characteristics, gill and stem features, habitat, and season. Leveraging machine learning techniques, the project provides insights and recommendations for identifying safe mushrooms for consumption.

## Table of Contents:
1. Introduction
2. Dataset Overview
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Preprocessing
6. Model Selection
7. Model Training
8. Model Evaluation
9. Hyperparameter Tuning
10. Feature Importance Analysis
11. Conclusion
12. Recommendations
13. Future Work
14. References

## Introduction:
Mushrooms are an essential part of various cuisines but can be dangerous if consumed without proper identification. This project addresses the need for accurately classifying mushrooms as edible or poisonous, highlighting the importance of food safety.

## Dataset Overview:
The dataset used in this project consists of mushroom samples with features such as cap diameter, cap shape, cap surface, gill color, stem height, and habitat. It contains 61,069 instances and 21 features. Data cleaning involved handling missing values, outliers, and removing duplicates.

## Data Cleaning:
The data cleaning process involved removing features missing more than 30% of their values and filling missing values with the mode for remaining features. Duplicate values were also removed to ensure data integrity.

## Exploratory Data Analysis (EDA):
EDA revealed insights into the distribution of features such as cap diameter and gill color among edible and poisonous mushrooms. Visualizations helped identify patterns and correlations within the dataset.

## Preprocessing:
Categorical variables were encoded, and feature scaling techniques were applied to prepare the data for model training. This ensured compatibility with machine learning algorithms.

## Model Selection:
Several algorithms were considered for classification, with Random Forest chosen for its Ensemble Nature and Robustness. The decision was based on the nature of the problem and the size of the dataset.

## Model Training:
The data was split into training and testing sets, and Random Forest was trained on the training data. This involved fitting the model to the training data to learn patterns and relationships.

## Model Evaluation:
Evaluation metrics such as accuracy, precision, recall, and F1-score were calculated to assess the performance of the trained model. The ROC-AUC curve and confusion matrix provided further insights into model performance.

## Hyperparameter Tuning:
Hyperparameters of the Random Forest model were fine-tuned using grid search cross-validation to optimize performance.

## Feature Importance Analysis:
Analysis of feature importance revealed insights into the factors contributing most to the model's predictions. This helped identify key features for distinguishing between edible and poisonous mushrooms.

## Conclusion:
The project successfully classified mushrooms as edible or poisonous based on various features. Insights gained from the analysis can aid in safe mushroom consumption practices.

## Recommendations:
Based on the analysis, recommendations for selecting edible vs. poisonous mushrooms include considering features such as cap diameter, cap color, gill attachment, and stem color. 
1. Cap Characteristics: Avoid Bell or Others cap shapes and mushrooms with Sticky, Fibrous, or Silky cap surfaces, indicating potential toxicity.
2. Gill and Stem Features: Choose mushrooms with Pores or Free gill attachments, White or Gray stem and gill colors for safer consumption.
3. Habitat and Season: Prefer mushrooms from Leaf litter habitats and exercise caution in Summer and Autumn.
4. Dimensions: Opt for mushrooms with moderate cap diameters, stem-width, and stem height, avoiding smaller ones.
5. Use Models as a Tool: Leverage machine learning models as additional tools for decision-making.
6. Combination of Features: Consider synergies between features for a more accurate assessment.
7. Regular Updates: Stay informed on the latest research and information regarding mushroom toxicity.
8. Exercise Caution: When uncertain, seek guidance from experts or avoid consuming wild mushrooms altogether.
Further research could explore additional features or enhance model performance.

## Future Work:
Future work could focus on expanding the dataset, exploring advanced machine learning algorithms, and integrating external sources for enhanced classification accuracy.

## References:
- Mushroom Dataset: [Link to Dataset](https://github.com/NKKesharwani/Mushroom_Classification_Edible_vs_Poisonous/blob/master/Data.csv)
