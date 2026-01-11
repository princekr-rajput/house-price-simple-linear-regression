## House Price Prediction using Simple Linear Regression

## 📌 Overview
This project demonstrates the use of **Simple Linear Regression** to predict house prices
based on **carpet area** using a real-world housing dataset sourced from **Kaggle**.
The project focuses on understanding regression fundamentals and analyzing the
limitations of using a single feature for price prediction.

---

## 📊 Dataset
- The original dataset was sourced from **Kaggle**
- The raw dataset contained multiple features and inconsistencies
- The data was **cleaned and preprocessed manually** to create a usable subset

### Data Cleaning Performed
- Removed irrelevant columns
- Extracted numeric values from text fields (e.g., "500 sqft")
- Handled missing values
- Retained only relevant features for this project:
  - **Area** (Carpet Area in sqft)
  - **Price** (House price)

The final cleaned dataset contains approximately **88,000 records**.

---

## 🧠 Model Used
- **Simple Linear Regression**
- Implemented using **scikit-learn**

Mathematical form:
Price = m × Area + c

---

## ⚙️ Workflow
1. Data cleaning and preprocessing
2. Feature and target selection
3. Train–test split
4. Model training
5. Prediction on unseen test data
6. Model evaluation
7. Visualization and interpretation

---

## 📈 Evaluation Metrics
- **Mean Squared Error (MSE)**
- **R² Score**

---

## 📉 Results & Analysis
- The **R² score is low**, indicating that carpet area alone is not sufficient
  to explain variations in house prices.
- Visualization shows **high variance** in prices for similar carpet areas.
- The regression line is nearly flat, indicating **underfitting**.

This behavior is expected for real-world housing data where price depends on
multiple factors such as location, number of rooms, amenities, and demand.

---

## 📊 Visualization
Scatter plots and regression lines were used to:
- Analyze the relationship between area and price
- Identify noise and outliers
- Interpret model limitations visually

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/princekr-rajput/house-price-simple-linear-regression.git
   cd house-price-simple-linear-regression
   pip install -r requirements.txt
   jupyter notebook
   ```
   

```md
## 📁 Project Structure

   house-price-simple-linear-regression/
   ├── Simple_linear_regression.ipynb   # Model training and evaluation
   ├── clean.ipynb                      # Data cleaning and preprocessing
   ├── house_price_clean_data.csv       # Cleaned dataset
   ├── requirements.txt                 # Project dependencies
   ├── README.md                        # Project documentation
   ├── LICENSE
   └── .gitignore
```
## 📌 Conclusion
This project demonstrates the application of Simple Linear Regression
on real-world housing data. The results show that using a single feature
(carpet area) is insufficient for accurate price prediction.

The project highlights the importance of data cleaning, visualization,
and honest evaluation when working with real datasets.

## 🔮 Future Work
- Apply Multiple Linear Regression using additional features
- Compare model performance improvements
- Explore non-linear regression models





