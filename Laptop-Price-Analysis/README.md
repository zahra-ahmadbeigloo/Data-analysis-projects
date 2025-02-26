# Laptop Price Analysis
## Overview
This project is designed to analyze laptop pricing data using various data science and machine learning techniques. I use libraries such as `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`, and `sklearn` to preprocess the data, perform exploratory data analysis (EDA), and build predictive models.

## Dependencies
Ensure you have the following packages installed:
- pandas
- numpy 
- seaborn
- matplotlib
- tqdm
- scipy
- scikit-learn

You can install them using:
````bash
pip install pandas numpy seaborn matplotlib tqdm scipy scikit-learn
````

## Data
The dataset used in this analysis is stored in a CSV file named `laptop_pricing_dataset_base.csv`. It contains information about laptop characteristics and their prices.

## Code Structure
- **Data Preprocessing**: The code loads the dataset, handles missing values, and scales numeric features.
- **Exploratory Data Analysis (EDA)**: Various visualizations are created to understand the relationships between features and the target variable (Price).
- **Feature Engineering**: Binning and dummy variable creation are performed.
- **Model Building**: Linear regression and Ridge regression models are built to predict laptop prices.
- **Model Evaluation**: The models are evaluated using metrics like R^2 score and mean squared error.

## How to Run
1. Clone the repository:
````bash
git clone [https://github.com/zahra-ahmadbeigloo/Data-analysis-projects] 
````
2. Navigate to the project directory:
````bash
cd Data_analysis_projects/Laptop_Price_Analysis
````
3. Open the Jupyter Notebook:
````bash
jupyter notebook Laptop-Price-Analysis.ipynb
````
4. Run all cells to execute the code within the notebook.

## Contact
For any queries, please contact [zaharaahmadbeigloo@gmail.com]
