# Thyroid Cancer Diagnosis Prediction

This project leverages machine learning techniques to predict thyroid cancer diagnosis based on medical data.

## Description

The notebook `Thyroid_Cancer_Diagnosis_Prediction.ipynb` contains data preprocessing, exploratory data analysis (EDA), and the implementation of machine learning models to assist in diagnosing thyroid cancer.

## Overview

This Notebook is designed to predict the Diagnosis (Benign/Malignant) of thyroid cancer using a dataset containing various patient attributes. It includes data exploration, visualization, and applying multiple machine-learning models.

## Dataset

- The dataset used in this notebook is titled 'Thyroid Cancer Risk Prediction Dataset' and is sourced from Kaggle. It contains various features related to patients, such as age, gender, smoking status, ethnicity, and diagnosis (they all have thyroid cancer).
- This dataset contains 212,691 records with 23 attributes, simulating real-world thyroid cancer risk factors. It is intentionally biased towards certain ethnicities, countries, and risk factors such as radiation exposure, iodine deficiency, and family history. The dataset can be used for machine learning modeling, bias detection, fairness analysis, and medical research simulations.

### Dataset Features

- **Patient_ID**: Unique identifier for each patient (int)
- **Age**: Age of the patient (int)
- **Gender**: Gender of the patient (categorical: Male, Female)
- **Country**: Patient's country of residence (categorical)
- **Ethnicity**: Ethnic background of the patient (categorical)
- **Family_History**: Family history of thyroid disease (categorical: Yes/No)
- **Radiation_Exposure**: Exposure to radiation (categorical: Yes/No)
- **Iodine_Deficiency**: Presence of iodine deficiency (categorical: Yes/No)
- **Smoking**: Smoking habit of the patient (categorical: Yes/No)
- **Obesity**: Whether the patient is obese (categorical: Yes/No)
- **Diabetes**: Presence of diabetes (categorical: Yes/No)
- **TSH_Level**: Thyroid-stimulating hormone level (float in mIU/L)
- **T3_Level**: Triiodothyronine level (float in ng/dL)
- **T4_Level**: Thyroxine level (float in mcg/dL)
- **Nodule_Size**: Size of thyroid nodules (float in cm)
- **Thyroid_Cancer_Risk**: Estimated cancer risk (categorical: Low, Medium, High)
- **Diagnosis**: Final diagnosis of thyroid cancer (target variable, categorical: Benign/Malignant)

## Notebook Structure

1. **Data Import and Setup**
   - Importing libraries such as pandas, matplotlib, seaborn, and scikit-learn.
   - Loading the dataset from Kaggle.

2. **Data Exploration and Visualization**
   - Gender Distribution: Pie chart visualization.
   - Smoking vs Diagnosis: Count plot analysis.
   - Ethnicity Distribution: Pie chart visualization.
   - Family History Analysis: Pie chart for family history of infection.
   - Thyroid Cancer Risk by Diagnosis, Country, and Family History: Count plots.

3. **Model Evaluation**
   - Evaluate models using accuracy, F1 score, recall, and precision.
   - Store results in a dictionary for comparison.

4. **Model Training and Prediction**
   - Train multiple models on training data.
   - Predict diagnosis on the test set and evaluate performance.

5. **Models Used**
   - KNN, Decision Tree, Random Forest, Logistic Regression, Gradient Boosting, AdaBoost, GaussianNB, ExtraTrees, MLP Classifier, and ANN.

6. **Results and Analysis**
   - Performance metrics for each model.
   - Visualization of results.
   - Classification report and confusion matrix.

## Prerequisites

To run this project, you need to have the following installed:

- Python 3.x
- Jupyter Notebook
- Required libraries (listed in `requirements.txt`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/thyroid-cancer-prediction.git
   cd thyroid-cancer-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `Thyroid_Cancer_Diagnosis_Prediction.ipynb` in your browser.

## Usage

- Load the dataset and explore the data.
- Preprocess the data to handle missing values and outliers.
- Train machine learning models (e.g., Logistic Regression, Random Forest, or Support Vector Machine).
- Evaluate the model's performance using accuracy, precision, recall, and F1-score.
- Visualize the results for better interpretation.

## Future Work

- Hyperparameter tuning for improved performance.
- Feature engineering to enhance accuracy.
- Deployment as a web application or API for real-time predictions.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Kaggle Dataset: Thyroid Cancer Risk Prediction]
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

