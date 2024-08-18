# Breast Cancer Prediction using Machine Learning

This project aims to predict the presence of breast cancer in patients using machine learning models. 
By analyzing features extracted from breast tissue, the model provides predictions on whether the tumor is benign or malignant.

###  **Dataset**
- Describe the dataset used, including its source, features, and how it's structured.
  

```markdown
## Dataset

The dataset used in this project is the [Breast Cancer Wisconsin (Diagnostic) Data Set] downloaded from kaggle.com

 **Features:** The dataset contains 30 features, including radius, texture, perimeter, area, and smoothness of the cell nuclei.
 **Target Variable:** The target variable is `diagnosis`, which indicates whether the tumor is benign (B) or malignant (M).

## Model Training

- **Preprocessing:** Data was normalized to ensure that all features contribute equally to the model's predictions.
- **Model:** A Random Forest Classifier was used for prediction due to its robustness and high accuracy.
- **Hyperparameter Tuning:** GridSearchCV was used to optimize the model parameters.


