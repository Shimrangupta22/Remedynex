# Remedynex

## Overview
The **Remedynex** is a machine learning-based drug recommendation system designed to predict potential diseases from user-input symptoms and provide personalized medication recommendations. The system aims to assist users by offering relevant drug suggestions, disease descriptions, precautions, and personalized health guidance.

## Features
- **Symptom-Based Disease Prediction**: Enter your symptoms to get the most likely disease predictions.
- **Medication Recommendations**: Receive suggestions for appropriate medications based on the predicted disease.
- **Precautionary Measures**: Access detailed advice on managing the predicted condition.
- **Dietary and Workout Suggestions**: Get personalized recommendations for diet and exercise tailored to the predicted condition.

## Datasets
The system utilizes a medical dataset containing symptoms, diseases, and corresponding medications. The dataset includes 4920 samples with 133 features.

## Key Dependencies
- **Python 3.8+**
- **scikit-learn**: For model training and predictions.
- **pandas**: For data manipulation.
- **numpy**: For numerical computations.

## How to Run
1. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
   
2. Open the notebook:
    ```bash
    jupyter notebook Drug_recommendation_system.ipynb
    ```

3. Run all cells to train the model and perform predictions.

4. Input your symptoms when prompted. The system will display:
    - Predicted disease
    - Description of the disease
    - Medication recommendations
    - Precautionary measures
    - Dietary suggestions
    - Workout recommendations

## Model Training
The dataset is divided into training and testing sets using an 80-20 ratio. The **Support Vector Classifier (SVC)** model is trained on symptom data to predict diseases.

## Example

After inputting your symptoms, the output will look like:
=================Predicted Disease================= Urinary Tract Infection

=================Description======================== A urinary tract infection (UTI) is an infection in any part of your urinary system...

=================Precautions=========================

Drink plenty of fluids
Avoid holding urine for too long
Urinate after sexual intercourse ...
=================Medications=========================

Nitrofurantoin
Trimethoprim-sulfamethoxazole ...
=================Dietary Suggestions=================

UTI Diet
Hydration
Cranberry juice ...
=================Workout Recommendations=============

Stay physically active
Engage in light exercises like walking or stretching ...

## Future Enhancements
- Expand the dataset to include more diseases and symptoms.
- Enhance the user interface and integrate the system into a web or mobile application.
- Develop a recommendation engine for consulting doctors or medical specialists based on the predicted condition.
