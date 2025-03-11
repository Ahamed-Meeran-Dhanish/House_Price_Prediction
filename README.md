# 🏡 House Price Prediction – Model Training  

## 📌 Project Overview  
This project aims to predict house prices based on features like **size, location, and build quality**. The dataset was cleaned, preprocessed, and analyzed to build an effective predictive model.  

## 🔹 Task 4: Model Training  

### **1️⃣ Train-Test Split**  
✔ The dataset was split into **80% training** and **20% testing** for fair evaluation.  
✔ Used `train_test_split` from `scikit-learn` with `random_state=42` to ensure reproducibility.  

### **2️⃣ Model Used: Linear Regression**  
- Implemented a **Linear Regression model** using `scikit-learn`.  
- Evaluated the model's performance on the test dataset.  

### **3️⃣ Model Performance Metrics**  
📌 **Mean Absolute Error (MAE):** ₹223,341.77  
📌 **Mean Squared Error (MSE):** ₹66.66 billion  
📌 **R² Score:** -0.00097  

### **4️⃣ Key Observations**  
⚠️ **Low R² score** indicates **Linear Regression is not capturing patterns effectively**.  
⚠️ **Weak feature correlations** are affecting prediction accuracy.  
⚠️ **Possible non-linear relationships** in the data.  

### **5️⃣ Next Steps**  
✅ **Explore non-linear models** (e.g., Random Forest, XGBoost).  
✅ **Improve feature engineering** to extract better insights.  
✅ **Handle outliers** to reduce high variance.  

## 🚀 **Installation & Usage**  
1️⃣ **Clone the repository**  
git clone https://github.com/your-username/House_Price_Prediction.git
cd House_Price_Prediction
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the model training script
python train_model.py
