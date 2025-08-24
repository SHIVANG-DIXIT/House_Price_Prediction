# 🏡 House Price Prediction

This project predicts the **price of houses** based on features such as number of bedrooms, bathrooms, living area, and year built.  
It uses **Linear Regression** as the predictive model after performing **data cleaning, outlier removal, and exploratory data analysis (EDA)**.  

---

## 🔹 Features of the Project
- Data Cleaning:
  - Removed irrelevant columns (`date`, `street`, `city`, `statezip`, `country`)
  - Outlier detection & removal using **IQR method**
- Exploratory Data Analysis (EDA):
  - Boxplots, histograms, correlation heatmaps
- Model Training:
  - Implemented **Linear Regression** with Scikit-learn
- Model Evaluation:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## 🔹 Dataset
The dataset (`house_price_data.csv`) contains information such as:
- **Price**  
- **Bedrooms**  
- **Bathrooms**  
- **Square footage (living area, lot, basement, above ground)**  
- **Floors**  
- **Waterfront, View, Condition**  
- **Year Built, Year Renovated**  


---

## 🔹 Tech Stack
- **Language**: Python  
- **Libraries**:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

---

