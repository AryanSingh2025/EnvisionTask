# Credit Card Fraud Detection

## Overview
This project is part of the **Team Envision Task**, a technical team of **Aaruush**. The goal is to detect fraudulent credit card transactions using machine learning techniques. The dataset consists of anonymized transaction details, and models are trained to distinguish between legitimate and fraudulent transactions with high accuracy.

## Dataset
- **File:** `envisionTask.csv`
- **Features:** Transaction-related numerical attributes.
- **Target Variable:** `Class` (0: Legitimate, 1: Fraudulent)

## Machine Learning Models
The project implements two machine learning models:
- **Logistic Regression:** A linear model used for binary classification.
- **Random Forest:** An ensemble learning method that improves fraud detection accuracy.

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required dependencies:
```bash
pip install pandas numpy scikit-learn
```

### Running the Model
1. Clone the repository:
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```
2. Run the training script:
```bash
python train_model.py
```

## Model Training Process
1. **Dataset Loading:** The dataset is loaded from `envisionTask.csv`.
2. **Feature Selection:** All columns except `Class` are used as input features.
3. **Train-Test Split:** The data is split into **80% training** and **20% testing**.
4. **Feature Scaling:** StandardScaler is applied to normalize the data.
5. **Model Training:**
   - **Logistic Regression** is trained using the scaled dataset.
   - **Random Forest Classifier** is trained using the unscaled dataset.
6. **Model Evaluation:**
   - Predictions are made on the test set.
   - Accuracy scores are calculated for both models.

## Evaluation Metrics
The models are evaluated using:
- **Accuracy**

## Results
Both models' accuracy is printed after evaluation, allowing comparison between Logistic Regression and Random Forest.

## License
This project is open-source and available under the MIT License.

## Contributions
Feel free to submit pull requests or open issues for improvements!
