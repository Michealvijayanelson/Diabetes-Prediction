
# Diabetes Prediction Using AdaBoost Classifier

## 📌 Project Overview
This project aims to predict whether a person is diabetic or not using machine learning techniques, specifically the **AdaBoost Classifier** from scikit-learn. The model is trained on medical data and evaluated for accuracy and performance.

## 🎯 Objective
The goal is to develop a machine learning model that can assist in early detection of diabetes based on health parameters.

## 🗂 Dataset
- File: `Book1.csv`
- Contains medical features and a target column indicating whether the patient is diabetic.
- Dataset preprocessing includes removing empty rows and checking for missing values.

## ⚙️ Workflow
1. **Install Dependencies**
   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```
2. **Load Dataset**
   - Uses Pandas to read and process the CSV file.
3. **Data Preprocessing**
   - Removes the last row if empty.
   - Checks for missing values.
4. **Split Dataset**
   - 80% training data, 20% test data using `train_test_split`.
5. **Train Model**
   - Model: `AdaBoostClassifier`
   - Random state: 96 (for reproducibility)
6. **Evaluate Model**
   - Calculates accuracy score.
   - Generates a confusion matrix to evaluate classification performance.

## 📊 Model Used
**AdaBoost Classifier**
- A boosting algorithm that combines multiple weak learners to create a strong learner.
- Good for binary classification tasks like diabetes prediction.

## 📈 Results
- Outputs an accuracy score for both training and testing sets.
- Displays a confusion matrix visualization.

## 🛠 Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/diabetes-prediction-ml.git
   ```
2. Navigate to the project directory:
   ```bash
   cd diabetes-prediction-ml
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Python script:
   ```bash
   python final_project_code.py
   ```

## 📌 Future Enhancements
- Test with other machine learning models for comparison.
- Integrate hyperparameter tuning to improve accuracy.
- Deploy as a web application for easier access.

---
**Author:** Micheal Vijaya Nelson A
