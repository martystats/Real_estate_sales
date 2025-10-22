# Cleaned_Real_Estate_Sales_2001-2022_GL.csvv2 — Real Estate Price Prediction Portfolio

This project presents a full machine learning pipeline applied to a real-world real estate dataset. The goal was to clean, explore, and build a predictive model to estimate property sale prices based on historical housing data from 2001 to 2022.

---

## Project Structure

- **Jupyter Notebook (`Clearworkflows002.ipynb`)**  
  Contains the full pipeline: data cleaning, EDA, feature engineering, model training, and export steps.

📂 Dataset Access
Due to GitHub’s 25 MB upload restriction, the full cleaned dataset is hosted externally on Dropbox.  
You can download it using the link below:  

🔗 (https://www.dropbox.com/scl/fo/u6ynr49xy29ws9ia3mj5l/AKZTy1724Yb6PbeNLFqSfNo?rlkey=b3wi7l0aauxhtvwww4cmpdnec&dl=1)
---

**Trained Model (`random_forest_model.pkl`)**
Due to GitHub’s 25 MB file size limit, the trained Random Forest model is also hosted externally on Dropbox.  
You can download it using the link below:


- **Dataset (`Cleaned_Real_Estate_Sales_2001-2022_GL.csvv2`)**  
  Preprocessed dataset containing cleaned and structured features used in the modeling process.

---

## Key Highlights

### 1. **Data Cleaning & Transformation**
- Removed outliers and duplicate records.
- Fixed inconsistent formats in dates and numerical fields.
- Converted categorical variables and optimized memory usage.

### 2. **Exploratory Data Analysis (EDA)**
- Visualized sale trends over years, property types, and towns.
- Identified key variables impacting price (e.g., size, location, year).

### 3. **Modeling**
- Trained multiple regression models: Linear Regression, Decision Tree, and Random Forest.
- Evaluated models using R² and Mean Squared Error (MSE).
- Selected the **Random Forest Regressor** for best performance.

### 4. **Export & Deployment**
- Exported trained model for reuse.
- All artifacts uploaded to GitHub for documentation and accessibility.

---

## Model Performance

- **Best Model**: Random Forest Regressor  
- **R² Score**: ~0.92  
- **MSE**: ~1.47e+07

---

## Author

**Martin Ude**  
GitHub: [martystats](https://github.com/martystats)

---

**Note:** This project was executed using Jupyter Notebook and version controlled with Git Bash.
