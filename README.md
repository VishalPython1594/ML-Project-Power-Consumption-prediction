# ⚡ Power Consumption Optimization in Zone 1 - Wellington, New Zealand

## 📌 Project Overview
This project focuses on optimizing **power consumption in Zone 1** of **Wellington, New Zealand**, using machine learning regression techniques. The model predicts power usage based on various **environmental and meteorological factors**, helping in energy management and efficiency improvements.

## 📊 Dataset & Data Dictionary
The dataset consists of **environmental and meteorological variables** that influence power consumption. Below are the key features:

| **Feature** | **Description** | **Units** |
|------------|----------------|-----------|
| **Sr No.** | Serial number of the record | - |
| **Temperature** | Temperature at the location | °C |
| **Humidity** | Relative humidity | g/m³ |
| **Wind Speed** | Speed of wind | Nautical mile/hour |
| **General Diffuse Flows** | Intensity of diffuse solar radiation | m²/s |
| **Diffuse Flows** | Measure of diffuse solar radiation | m²/s |
| **Air Quality Index** | Air pollution level | µg/m³ |
| **Cloudiness** | Presence of clouds (1: Yes, 0: No) | Binary |
| **Zone 1 Power Consumption** | **Target variable - Power consumption in the zone** | kWh |

---

## 🏗️ **Project Workflow & Methodology**
The project follows a structured **machine learning pipeline**:

### **1️⃣ Data Preprocessing & Feature Engineering**
✅ **Handling missing values** using imputation.  
✅ **Feature scaling** (Standardization & Normalization).  
✅ **Creating new interaction features** for better prediction.  
✅ **Encoding categorical variables** (Cloudiness).  

### **2️⃣ Exploratory Data Analysis (EDA)**
✅ **Correlation analysis** to understand feature importance.  
✅ **Outlier detection & treatment** using statistical methods.  
✅ **Visualizing relationships between variables and power consumption.**  

### **3️⃣ Regression Model Building**
✅ **Baseline models**: Linear Regression, Decision Tree Regression.  
✅ **Advanced models**: Random Forest, XGBoost, LightGBM.  
✅ **Hyperparameter tuning** using GridSearchCV & RandomizedSearchCV.  

### **4️⃣ Dimensionality Reduction**
✅ **Principal Component Analysis (PCA)** to reduce redundancy in data.  
✅ **Feature selection** using Mutual Information & Recursive Feature Elimination (RFE).  

### **5️⃣ Model Evaluation & Optimization**
✅ **Metrics used**:  
   - **Mean Absolute Error (MAE)**  
   - **Mean Squared Error (MSE)**  
   - **Root Mean Squared Error (RMSE)**  
   - **R² Score (Coefficient of Determination)**  
✅ **Comparing models** to select the best-performing one.  

---

## ⚙️ **Technologies & Tools Used**
- **Python** (Programming Language)
- **Pandas, NumPy** (Data Processing)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-Learn** (Machine Learning Models)
- **XGBoost, LightGBM** (Advanced ML Models)
- **GridSearchCV, PCA** (Hyperparameter Tuning & Feature Reduction)

---

## 🚀 **Installation & Setup**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/VishalPython1594/ML-Project-Power-Consumption-prediction.git
   cd Power-Consumption-ML
   ```
   
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   
3. **Run the model**:
   ```bash
   python power_consumption_prediction.py
   ```

## 🏆 Certification
This project is certified by **Learnbay**.

[Certificate]![image](https://github.com/user-attachments/assets/ed824ca6-bd62-46ac-acc7-f8a270b4c179)

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request if you have improvements or new features.

## 📜 License
This project is licensed under the MIT License.

## 📩 Contact & Support
📧 Email: vishal1594@outlook.com
🔗 LinkedIn: https://www.linkedin.com/in/vishal-shivnani-87487110a/
