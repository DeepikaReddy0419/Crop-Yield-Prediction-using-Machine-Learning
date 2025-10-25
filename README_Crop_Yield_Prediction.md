# 🌾 Crop Yield Prediction using Machine Learning

### 🎯 Objective
Predict agricultural **crop yield** using environmental and soil features like rainfall, temperature, fertilizer usage, and soil type through machine learning regression models.

### 🧠 Overview
This project applies **supervised learning** techniques to estimate crop yield based on weather and soil data. By training models such as **Linear Regression**, **Random Forest**, and **XGBoost**, the system helps farmers and policymakers make better agricultural decisions.

### 📊 Dataset
**Source:** FAO / Synthetic Crop Yield Dataset  
**Attributes:**
| Feature | Description |
|----------|--------------|
| State | Region or state name |
| Crop | Type of crop (Rice, Wheat, Maize, etc.) |
| Rainfall | Average annual rainfall (mm) |
| Temperature | Mean temperature (°C) |
| Soil Type | Soil category (Clay, Sandy, Loamy) |
| Fertilizer Usage | Fertilizer used (kg/ha) |
| Yield | Target variable (tons/ha) |

> The dataset used here is synthetic (for demonstration) but modeled on FAO-style crop yield data.

### ⚙️ Techniques Used
- **Machine Learning Models**
  - Linear Regression  
  - Random Forest Regressor  
  - XGBoost Regressor  
- **Feature Engineering**
  - Label Encoding for categorical variables  
  - Feature Scaling using `StandardScaler`  
- **Model Evaluation Metrics**
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  

### 🧩 Skills Demonstrated
- Supervised Learning (Regression)
- Data Cleaning & Preprocessing  
- Feature Engineering  
- Model Training & Evaluation  
- Model Deployment (Pickle file)

### 🗂️ Project Structure
```
📦 Crop-Yield-Prediction
 ┣ 📂 data
 ┃ ┗ crop_yield.csv
 ┣ 📂 models
 ┃ ┗ best_crop_yield_model.pkl
 ┣ 📂 notebooks
 ┃ ┗ Crop_Yield_Prediction.ipynb
 ┣ 📄 crop_yield_prediction.py
 ┣ 📄 requirements.txt
 ┗ 📄 README.md
```

### 🚀 How to Run
#### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/Crop-Yield-Prediction.git
cd Crop-Yield-Prediction
```

#### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

#### 3️⃣ Run the main script
```bash
python crop_yield_prediction.py
```

#### 4️⃣ Output
- Model performance (MSE, RMSE, R²)
- Saved model: `best_crop_yield_model.pkl`
- Sample prediction result

### 🧾 Sample Output
```
📊 Model Performance Comparison:

Linear Regression: MSE=8.931, RMSE=2.989, R²=0.875
Random Forest: MSE=6.124, RMSE=2.474, R²=0.912
XGBoost: MSE=5.832, RMSE=2.414, R²=0.918

✅ Best model saved: XGBoost -> 'best_crop_yield_model.pkl'
🌾 Predicted Crop Yield for sample input: 19.82 tons/ha
```

### 📚 Future Improvements
- Include additional features (humidity, soil pH, irrigation)  
- Deploy the model using **Streamlit** or **Flask**  
- Integrate real FAO / Kaggle datasets  
- Automate data updates with weather APIs  

### 👨‍💻 Author
**Yellampalli Mani Deepika**  
_Data Science Project | Regression | Agriculture Analytics_
