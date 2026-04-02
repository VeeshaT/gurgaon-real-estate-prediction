# 🏠 Gurgaon Real Estate Price Prediction

**Semester 6 ML Project | Category: Regression | Student: VeeshaT**

---

## 📌 Problem Statement
Predict residential property prices in Gurgaon using machine learning regression techniques based on features like location, size, amenities, and more.

---

## 📊 Dataset
- **Records:** 800+ property listings
- **Localities:** 20 areas across Gurgaon
- **Features:** 11 input features + 1 target variable (Price in Lakhs)

| Feature | Description |
|---|---|
| Locality | Area in Gurgaon (e.g. DLF, Golf Course Road) |
| BHK | Number of bedrooms (1-5) |
| Area_sqft | Total area in square feet |
| Floor | Floor number |
| Age_years | Age of property |
| Parking | Number of parking spots |
| Furnishing | Furnished / Semi / Unfurnished |
| Status | Ready to Move / Under Construction |
| Gym / Pool / Security | Amenity availability |

---

## 🔄 Workflow
1. Data Collection & Loading
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering & Encoding
5. Model Training & Evaluation
6. Best Model Selection & Prediction

---

## 📈 Exploratory Data Analysis

<img width="888" height="631" alt="image" src="https://github.com/user-attachments/assets/d2f9193e-8965-44ea-9e51-1e874a047845" />


---

## 🤖 Models Used & Results

| Model | R² Score | MAE (Lakhs) | RMSE (Lakhs) |
|---|---|---|---|
| Linear Regression | 0.9130 | 18.54 | 23.06 |
| Ridge Regression | 0.9131 | 18.55 | 23.05 |
| Lasso Regression | 0.9135 | 18.61 | 22.99 |
| Random Forest | 0.9803 | 8.30 | 10.96 |
| **Gradient Boosting** | **0.9916** 🏆 | **5.51** | **7.18** |

<img width="1363" height="575" alt="image" src="https://github.com/user-attachments/assets/7d024dfe-f0ae-41d6-8808-c693ac4a1c9b" />


---

## 🌲 Feature Importance

<img width="1057" height="625" alt="image" src="https://github.com/user-attachments/assets/760163ca-31b6-4c21-9b0d-df2a1226285f" />


---

## 🏠 Sample Prediction

| Property Detail | Value |
|---|---|
| Locality | Golf Course Road |
| BHK | 3 |
| Area | 1800 sq ft |
| Floor | 7th |
| Age | 3 years |
| Furnishing | Semi-Furnished |
| Amenities | Gym + Pool + Parking + Security |

### 💰 Predicted Price: ₹ 167.43 Lakhs (≈ ₹ 1.67 Crores)

---

## ✅ Conclusion
- **Gradient Boosting** achieved the best R² of **0.9916**
- **Area, Locality & BHK** are the top 3 price drivers
- Model can assist buyers, sellers & investors in making informed decisions

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook
