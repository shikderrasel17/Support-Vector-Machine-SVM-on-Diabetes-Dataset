# Support Vector Machine (SVM) on Diabetes Dataset

## Model Details
This repository features an implementation of the Support Vector Machine (SVM) classifier to predict diabetes based on health-related data.

## Intended Use
The project is designed for educational purposes, showcasing the application of SVM in a real-world healthcare dataset.

## Data Source
The diabetes dataset is utilized, consisting of several predictor variables and a binary target variable `Outcome`.

## Dataset Sample
| Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin | BMI  | DiabetesPedigreeFunction | Age | Outcome |
|-------------|---------|---------------|---------------|---------|------|--------------------------|-----|---------|
| 6           | 148     | 72            | 35            | 0       | 33.6 | 0.627                    | 50  | 1       |
| 1           | 85      | 66            | 29            | 0       | 26.6 | 0.351                    | 31  | 0       |
| 8           | 183     | 64            | 0             | 0       | 23.3 | 0.672                    | 32  | 1       |
| 1           | 89      | 66            | 23            | 94      | 28.1 | 0.167                    | 21  | 0       |

## Training Data
- **Split**: 80% training, 20% testing
- **Features**: `Pregnancies`, `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`, `DiabetesPedigreeFunction`, `Age`
- **Target**: `Outcome`

## Test Data
- 20% of the dataset reserved for testing the models.

## Parameters
- **SVM Parameters**: Default settings were used for the SVM classifier.

## Feature Importance
Although SVM does not inherently provide feature importance, the analysis and visualization of the features' impact were performed using alternative methods.

## Metrics
- **Accuracy**: Determined through cross-validation and test data.
- **Classification Report**:
  - Precision, recall, F1-score for each class
  - Macro and weighted averages

## How to Run
1. Load the dataset.
2. Preprocess the data as needed.
3. Train the SVM model using the provided code.
4. Evaluate the model performance using various metrics.

## Additional Information
- Libraries used: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
- Visualization includes sample plots and confusion matrices.
