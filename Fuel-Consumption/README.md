# 🚗 CO₂ Emissions Prediction using Linear & Polynomial Regression

This project explores the relationships between vehicle engine attributes (e.g., engine size, fuel consumption) and CO₂ emissions using various regression techniques. The dataset used is from Natural Resources Canada (NRCAN), and includes features such as engine size, cylinders, fuel consumption (city, highway, combined), and CO₂ emissions.

## 📁 Dataset

The dataset used is:
```
FuelConsumption.csv
```
Each row in the dataset represents a specific car model with the following selected columns:
- `ENGINESIZE`: Engine size in liters
- `CYLINDERS`: Number of cylinders
- `FUELCONSUMPTION_COMB`: Combined fuel consumption in L/100km
- `FUELCONSUMPTION_COMB_MPG`: Miles per gallon (inverted fuel consumption)
- `CO2EMISSIONS`: Emissions of CO₂ in grams/km

---

## 📊 Project Objectives

- Perform **exploratory data analysis (EDA)** and visualize feature distributions.
- Build **simple and multiple linear regression models**.
- Compare performance of:
  - **Standard Linear Regression**
  - **Ridge Regression**
  - **Lasso Regression**
- Apply **feature scaling** for improved model performance.
- Extend models using **Polynomial Regression** with hyperparameter tuning (degree, regularization).
- Visualize model performance and fit (2D and 3D plots).

---

## 🛠️ Technologies Used

- Python
- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn` – data visualization
- `scikit-learn` – machine learning models
- `mpl_toolkits.mplot3d` – 3D visualization

---

## 📈 Regression Models & Metrics

Each model was evaluated using:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Explained Variance Score**

Model types:
- Simple Linear Regression (1 feature)
- Multiple Linear Regression (2 features)
- Multiple Linear Regression with Polynomial Features
- Standardized Linear Regression
- Ridge & Lasso with Polynomial Features

---

## 🔍 Visualizations

- Histograms and scatterplots for EDA
- Regression lines and surfaces
- 3D scatterplot with regression plane
- Evaluation metrics comparison (Ordinary, Ridge, Lasso)
- Hyperparameter tuning plots (α, degree)

---

## 🧪 Example Evaluation Output

```text
Evaluation metrics for Ordinary Linear Regression
explained_variance:  0.8395
r2:  0.8395
MAE:  13.5678
MSE:  341.2309
RMSE:  18.4693
```

---

## 📌 How to Run

1. Clone the repository or copy the `.py` file.
2. Place the `FuelConsumption.csv` dataset in the same directory.
3. Run the script in a Jupyter notebook or your preferred Python environment.
4. Ensure required libraries are installed:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn tqdm
   ```

---

## 📎 Notes

- This script is educational and demonstrates the impact of model complexity, feature engineering, and regularization on regression tasks.
- Feature scaling is crucial when using Ridge and Lasso.
- Polynomial degree and alpha tuning play a key role in avoiding overfitting.

---

## 📚 Future Improvements

- Add cross-validation
- Incorporate additional features (e.g., vehicle class, transmission type)
- Deploy model with an interactive UI

---

## 🧠 Author

**Zahra Ahmadbeigloo**  
