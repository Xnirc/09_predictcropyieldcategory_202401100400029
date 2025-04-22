# 🌾 Crop Yield Prediction using Machine Learning

This project uses a **Random Forest Classifier** to predict crop **Yield Categories** based on features like **Soil Quality**, **Rainfall**, and **Seed Type**. It's a beginner-friendly machine learning pipeline built with **Python** and **scikit-learn**, and is designed to help farmers, agronomists, and researchers make informed decisions.

## 🚀 Features

- Predicts yield category (e.g., Low, Medium, High)
- Handles categorical data using label encoding
- Uses Random Forest for robust classification
- Simple, well-commented code — perfect for learning!

## 🧠 Tech Stack

- Python
- Pandas
- Scikit-learn
- Google Colab

## 📁 Dataset Format

The dataset should be in CSV format and include the following columns:

| Soil_Quality | Rainfall | Seed_Type | Yield_Category |
|--------------|----------|-----------|----------------|

**Note:** `Seed_Type` and `Yield_Category` can be categorical (e.g., "Wheat", "High").

## 📌 How to Run

1. Clone the repo or open in Google Colab
2. Upload your dataset CSV
3. Run all cells to train the model and evaluate accuracy

## 🔍 Sample Code

```python
model = RandomForestClassifier(n_estimators=100, random_state=42)
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
print("Accuracy:", accuracy_score(y_test, y_pred))

output - ![image](https://github.com/user-attachments/assets/bba1ebff-1fa5-480f-9cce-645ffaffd8c0)
