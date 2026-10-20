# 🚗 Car Price Prediction using Machine Learning

An end-to-end Machine Learning project to predict used car prices based on vehicle specifications using Linear Regression.

---

## 📌 Project Overview
The objective of this project is to build a regression model that accurately estimates vehicle prices based on multiple features like model, engine size, mileage, and vehicle age.

---

## 📊 Dataset Features
- **Make & Model**: Brand and model line of the vehicle.
- **Year / Car Age**: Manufacturing year and calculated vehicle age.
- **Engine Size**: Engine displacement capacity.
- **Mileage**: Total kilometers driven.
- **Fuel Type & Transmission**: Engine fuel system and gearbox type.
- **Price (Target)**: Actual market price of the car.

---

## ⚙️ Data Preprocessing & Pipeline
1. **Exploratory Data Analysis (EDA)**: Visualized distributions and category frequencies.
2. **Outlier Removal**: Filtered extreme pricing outliers to stabilize the model.
3. **Feature Engineering**: Extracted vehicle age (`car age`) from release year.
4. **Encoding & Scaling**:
   - `OneHotEncoder` for categorical features (avoiding dummy variable trap).
   - `StandardScaler` for numerical scaling and target normalization.

---

## 📈 Model Performance
- **Algorithm**: Linear Regression
- **Training Accuracy ($R^2$)**: **83.91%**
- **Testing Accuracy ($R^2$)**: **83.11%**
- **Root Mean Squared Error (RMSE)**: ~ **$2,053**

---

## 🛠️ Tech Stack
- **Language**: Python
- **Environment**: Fedora Linux, VS Code, Jupyter Notebook
- **Libraries**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Joblib