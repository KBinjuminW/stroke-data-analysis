# Stroke Prediction Using Machine Learning

## Project Overview
This project aims to predict whether a person will have a stroke based on various features such as age, gender, hypertension, heart disease, smoking status, and others. The dataset used contains demographic and medical data, and we applied a machine learning model to classify the likelihood of a stroke.

## Dataset
The dataset used in this project is the [Stroke Prediction Dataset](https://www.kaggle.com/datasets/your-dataset-link). It contains information on patient demographics and health conditions. The dataset is provided as a CSV file and includes various features such as:
- Age
- Gender
- Hypertension
- Heart disease
- Smoking status
- Stroke (target label)

## Files in This Repository
- `Stroke.ipynb` – Jupyter notebook with the full analysis and machine learning model implementation.
- `README.md` – This file, providing project details.
- Additional scripts (if any) related to data preprocessing and evaluation.

## Machine Learning Model
A machine learning model has been implemented to predict the likelihood of a stroke. The following steps were performed:
1. **Data Cleaning**: Missing values were handled, and categorical variables were encoded.
2. **Feature Engineering**: Relevant features were selected and prepared for modeling.
3. **Model**: A Random Forest classifier was used to predict stroke occurrence.
4. **Evaluation**: The model was evaluated using accuracy, precision, recall, and F1-score. Adjustments to the classification threshold were made to balance the prediction results.

### Model Performance
- **Accuracy**: 94.62%
- **Precision**: 95.21% (for class 0)
- **Recall**: 5.21% (for class 1)
- **F1-score**: 6.01% (for class 1)

In addition to the initial model, various techniques, including resampling methods such as SMOTE, were tested to address class imbalance.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stroke-data-analysis.git
