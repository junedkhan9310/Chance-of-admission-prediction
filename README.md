# Student Chance of Admission Prediction in Higher Studies

## Overview

This project aims to predict the chances of admission of a student to a university's graduate program based on various parameters such as GRE scores, TOEFL scores, university rating, statement of purpose, letter of recommendation strength, undergraduate CGPA, and research experience. The prediction model will utilize machine learning techniques to analyze the dataset and generate accurate predictions.

## Dataset

The dataset used for this project can be found [here](https://github.com/ybifoundation/Dataset/raw/main/Admission%20Chance.csv). It contains the following columns:

- GRE Scores (290 to 340)
- TOEFL Scores (92 to 120)
- University Rating (1 to 5)
- Statement of Purpose (1 to 5)
- Letter of Recommendation Strength (1 to 5)
- Undergraduate CGPA (6.8 to 9.92)
- Research Experience (0 or 1)
- Chance of Admit (0.34 to 0.97)

## Requirements

To run this project, you will need:

- Python 3.x
- Required libraries: `pandas`, `scikit-learn`

You can install the necessary libraries using pip:

```bash
pip install pandas scikit-learn
```

## Usage

1. Run the main script to train the model and make predictions.

```bash
python admission_prediction.py
```

4. Follow the prompts to input values for the parameters (GRE scores, TOEFL scores, etc.) for which you want to predict the chance of admission.

## Implementation Details

### Data Preprocessing

- The dataset is loaded using the `pandas` library.
- Data cleaning and preprocessing techniques are applied to handle missing values and ensure data integrity.

### Model Training

- A machine learning model, such as linear regression or random forest, is trained on the preprocessed dataset to predict the chance of admission.
- Model evaluation techniques, such as cross-validation, may be employed to assess the performance of the trained model.

### Prediction

- Once the model is trained, users can input their own values for the parameters to predict their chance of admission.
- The model will output a predicted chance of admission based on the provided input.

## File Structure

- `admission_prediction.py`: Main script containing the implementation of the admission prediction model.
- `README.md`: This file providing an overview of the project.
- `Admission_Chance.csv`: Dataset containing the admission-related parameters.

## Contributors

- [Khan Juned](https://github.com/junedkhan9310) - Project Developer
