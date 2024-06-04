# Disease_prediction_from_medial_data

**Diabetes Prediction Model**

 Overview
This project focuses on predicting the likelihood of diabetes based on medical data. Using a Random Forest classifier, the model analyzes various features such as symptoms, patient history, and other medical factors to provide accurate predictions. 

 Features
- Data Preprocessing: Handling missing values and feature scaling.
- Model Training: Utilizing Random Forest algorithm with hyperparameter tuning via GridSearchCV.
- Prediction: Predicting the likelihood of diabetes occurrence based on user input.
- **Model Evaluation**: Evaluating model performance with metrics such as accuracy score, confusion matrix, and ROC curve.
- **Visualization**: Visualizing the confusion matrix and ROC curve for better understanding of model performance.

### Dataset
The dataset used in this project includes labeled medical records with features such as:
- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

### Installation
To run this project, ensure you have the necessary libraries installed:
```bash
pip install pandas scikit-learn seaborn matplotlib
```

### Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/diabetes-prediction-model.git
    cd diabetes-prediction-model
    ```
2. **Run the script**:
    ```bash
    python diabetes_prediction.py
    ```

### Example Input
For the most critical case, you can use the following example values:
- Number of Pregnancies: 15
- Glucose Level: 200 mg/dl
- Blood Pressure: 100 mmHg
- Skin Thickness: 50 mm
- Insulin Level: 300 units/ml
- BMI: 40 kg/m^2
- Diabetes Pedigree Function: 1.0
- Age: 60 years

### Output
The model will provide the likelihood of diabetes occurrence as a percentage and indicate the risk level.

### Visualizations
- **Confusion Matrix**: Provides insight into the true positives, true negatives, false positives, and false negatives.
- **ROC Curve**: Illustrates the performance of the classifier at various threshold settings.

### Contributing
Feel free to fork this repository, make improvements, and submit a pull request. All contributions are welcome!

### License
This project is licensed under the MIT License.

### Tags
`#DiabetesPrediction` `#MachineLearning` `#RandomForest` `#HealthcareAI` `#MedicalData` `#HealthTech` `#DataScience` `#PreventiveMedicine` `#ModelEvaluation` `#DataVisualization`

---

Feel free to adjust the repository URL, example values, and any other details as needed. This post provides a comprehensive overview of the project, including installation instructions, usage examples, and a brief description of the model's features.
