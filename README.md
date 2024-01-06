# Comparative Machine Learning Study to Predict Social Media Addiction in Bangladesh

## Project Overview

Welcome to the GitHub repository for the research project "A Comparative Machine Learning Study to Predict Social Media Addiction in Bangladesh." This project explores the application of various machine learning models to predict social media addiction among individuals in the context of Bangladesh.

## Objective

The primary objective of this research is to conduct a comprehensive comparative study of machine learning models for predicting social media addiction. We aim to evaluate model performance, analyze feature importance, conduct exploratory data analysis (EDA), preprocess data, and provide insights into social media addiction in Bangladesh.

## Key Components

- **Code:** The `code` directory contains the Python scripts and Jupyter notebooks used for data analysis, model training, and evaluation.

- **Data:** The `data` directory includes the dataset used for the study. [Dataset Source]([link-to-dataset](https://www.kaggle.com/datasets/mdmasum789/social-media-addiction/data))

- **Visualizations:** The `visualizations` directory holds visualizations generated during the exploratory data analysis and model interpretation stages.

- **Models:** The `models` directory stores trained machine learning models.

- **Documentation:** The `docs` directory includes project-related documents, such as the project proposal, thesis paper, and any supplementary materials.

## Getting Started

Follow these steps to get a copy of the project up and running on your local machine:

1. Clone the repository: `git clone https://github.com/masumcse22/Social-Media-Addiction-in-ML`

2. Install dependencies: `pip install -r requirements.txt`

3. Navigate to the `code` directory and run the scripts or notebooks as needed.

## Requirements

- Python 3.5 or later
- Jupyter Notebook
- Anaconda

## Results

--------- Single Classifier Accuracy---------
- Random Forest(RF): 95.30
- Ada Boost(AdaB): 95.30
- XGBClassifier(xgb): 94.87
- GradientBoostingClassifier(GRA): 95.30
- KNeighborsClassifier(Knn): 95.30
- Naive_Bayes(nb): 95.09
- LogisticRegression(lr): 95.30
- DecisionTreeClassifier(dt): 95.30
- Suupport Vector Machine(SVM): 95.30

## Future Work

While the current study provides valuable insights into predicting social media addiction in Bangladesh, there are several avenues for future research and improvement. The following areas represent potential directions for extending and enhancing this project:

### 1. **Integration of External Datasets:**
   - Explore the possibility of integrating additional datasets related to social media usage patterns, demographics, or cultural factors in Bangladesh. Incorporating diverse data sources may enhance the model's predictive capabilities.

### 2. **Temporal Analysis:**
   - Conduct a temporal analysis to investigate how social media addiction trends evolve over time. This could involve collecting data at different time points to identify patterns, changes in user behavior, and emerging trends.

### 3. **Feature Engineering:**
   - Experiment with advanced feature engineering techniques to create more informative features. This could involve extracting additional insights from text data, sentiment analysis, or incorporating external information related to social media platforms.

### 4. **Ensemble Models:**
   - Implement ensemble learning techniques to combine predictions from multiple models. Ensemble methods, such as stacking or blending, could potentially improve overall predictive performance.

### 5. **Explanability and Interpretability:**
   - Enhance the interpretability of the models by utilizing techniques such as SHAP (SHapley Additive exPlanations) values or LIME (Local Interpretable Model-agnostic Explanations). This will help in understanding the key factors contributing to social media addiction predictions.

### 6. **Cross-Cultural Analysis:**
   - Extend the study to include cross-cultural analysis by comparing social media addiction prediction models across different regions or demographics within Bangladesh. This can provide insights into variations in social media usage patterns.

### 7. **Longitudinal Study:**
   - Consider conducting a longitudinal study to observe individuals' social media behavior over an extended period. This can offer a deeper understanding of the development of social media addiction and how it changes over time.

### 8. **User Engagement Strategies:**
   - Collaborate with psychologists or behavioral experts to devise strategies for responsible and positive social media use. Develop interventions or awareness campaigns based on the insights gained from the predictive models.

### 9. **Scalability and Deployment:**
   - Explore the scalability of the models to handle larger datasets or real-time prediction scenarios. Develop deployment strategies for integrating the models into social media platforms or mental health applications.

### 10. **User Feedback Integration:**
    - Incorporate user feedback into the models' training and evaluation process. Consider user surveys or feedback mechanisms to refine and improve model predictions based on users' self-reported experiences.

## Contributors

- [MD MASUM] - Project Lead - Implemented data preprocessing and model training.
- [MD FAYSAL RABBI] - Data Analyst - Conducted exploratory data analysis.
- [SAJAL ASFAK ROBIN] - Model Evaluator - Evaluated model performance and provided insights.

