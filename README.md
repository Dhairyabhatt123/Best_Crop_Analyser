DEMO LINK: https://best-crop-analyser.onrender.com

# 🌾 Crop Recommendation System using Machine Learning

This project is a **Crop Recommendation System** built using machine learning techniques. Based on essential soil and weather parameters, the model predicts the most suitable crop to cultivate in a particular region.

The model was trained on an open-source agricultural dataset and includes a **Streamlit-based UI** for real-time predictions.

---

## 🎯 Objective

To help farmers and agricultural experts by recommending the best crop to grow based on:
- **Soil nutrients**: Nitrogen (N), Phosphorus (P), Potassium (K)
- **Weather**: Temperature, Humidity, Rainfall
- **Soil pH**

---

## 📊 Dataset Features

The dataset includes the following columns:

- `N` – Nitrogen content in soil  
- `P` – Phosphorus content in soil  
- `K` – Potassium content in soil  
- `temperature` – in °C  
- `humidity` – in %  
- `ph` – Soil pH value  
- `rainfall` – in mm  
- `label` – Crop name (target variable)

---

## 🔧 Technologies & Libraries Used

- Python 🐍
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `scikit-learn` – Machine learning algorithms
- `Streamlit` – Web-based UI
- `pickle` – Model serialization

---

## 🚀 How the Model Was Built

1. **Data Preprocessing**
   - Checked for missing values
   - Normalized/Scaled data
   - Label encoding for target

2. **Exploratory Data Analysis**
   - Visualized distributions and relationships
   - Correlation heatmaps to find important features

3. **Model Selection**
   - Tested models: Logistic Regression, SVM, Decision Tree, Random Forest, Gradient Boosting
   - Tuned hyperparameters using `GridSearchCV`
   - Evaluated using accuracy and confusion matrix

4. **Deployment**
   - Saved the trained model and scalers using `pickle`
   - Built an interactive UI with Streamlit for user input and predictions

---

Users can input:
- N, P, K values
- Temperature, Humidity, pH, Rainfall

The app returns:
✅ The most recommended crop to be cultivated.

---

## 💡 Learnings

- Handling agricultural datasets
- Importance of feature scaling in real-world data
- Building interactive ML applications with Streamlit
- End-to-end deployment with real-time prediction
