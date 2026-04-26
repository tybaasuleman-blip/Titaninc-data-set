# Titanic Survival Prediction

This project analyzes the Titanic dataset to predict passenger survival using machine learning.

## 🛠️ Preprocessing Steps
- **Data Cleaning:** Handled missing values for `Age` (Mean Imputation), `Embarked` (Mode), and `Cabin` (Feature Engineering).
- **Feature Engineering:** Created a binary feature for `Cabin` (Known vs. Unknown).
- **Encoding:** Converted categorical text (`Sex`, `Embarked`) into numerical values using `LabelEncoder`.
- **Scaling:** Applied `MinMaxScaler` to `Age` and `Fare` to normalize values between 0 and 1.
- **Feature Selection:** Dropped non-predictive columns like `PassengerId`, `Name`, and `Ticket`.

## 🚀 How to Use
1. Open the notebook in Google Colab.
2. Run the preprocessing cells to clean the data.
3. Train the model (Random Forest recommended) to predict survival.

## 📊 Results
The model achieves a survival prediction accuracy of approximately **XX%** (fill in your result here!).
