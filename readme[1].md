# Meningioma Grade Prediction using Machine Learning and Radiomics Features

This repository contains code for predicting meningioma grades based on radiomics features extracted from MRI scans using machine learning techniques. The analysis focuses on differentiating between Grade 1 (benign) and Grade 2 (atypical) meningiomas using a dataset of 94 patients diagnosed between 2010 and 2019.

## Dataset Description
- The dataset comprises radiomics features extracted from pre-operative MRI scans of 94 patients with meningiomas.
- Features include size zones, gray levels, skewness, run variability, and other relevant characteristics.
- Each data point corresponds to a patient with 50 features recorded, including the tumor grade (Grade I or Grade II).

## Code Overview
1. **Data Wrangling**: The dataset is loaded and processed to remove unnecessary columns and ensure data consistency.
2. **Preliminary Data Analysis**:
   - Basic information about the dataset is displayed, including the unique grade classes and data configuration.
   - Data preprocessing steps are performed to prepare the dataset for model training.
3. **Model Building**:
   - Three machine learning models (Logistic Regression, Random Forest, Support Vector Machine) are trained to classify meningioma grades.
   - Hyperparameter tuning is applied to optimize model performance.
4. **Performance Analysis**:
   - The models' performance is evaluated before and after hyperparameter tuning.
   - The impact of SMOTE oversampling on imbalanced datasets is assessed.

## Results
- The trained models demonstrate varying levels of accuracy in predicting meningioma grades (details provided in the analysis report).
- Feature importance analysis reveals the significant radiomics features contributing to grade prediction.
- Limitations of the dataset, such as the exclusion of Grade III tumors, are discussed in the context of model generalizability.

## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Jupyter notebook or Python scripts provided to replicate the analysis and explore the results.

---

By incorporating information from the document, this README file provides a comprehensive overview of the meningioma grade prediction project, including dataset details, code processes, results, and instructions for usage.