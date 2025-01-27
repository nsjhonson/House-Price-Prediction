# House Price Prediction using TensorFlow Decision Forests

This project predicts house prices using the *House Prices: Advanced Regression Techniques* dataset from Kaggle. It leverages *TensorFlow Decision Forests (TF-DF)* to build a Random Forest regression model, providing accurate predictions and insights into the factors influencing house prices.

---

## 📂 Project Structure
- data/  
  Contains the training and test datasets used for model development.
- house-prices-prediction-using-tfdf.ipynb  
  Jupyter Notebook with data preprocessing, model training, evaluation, and predictions.
- README.md  
  This file with an overview of the project.
- submission.csv  
  File containing the final predictions for Kaggle submission.

---

## 🚀 Features
- *Data Preprocessing*: 
  - Handle mixed data types (numerical and categorical).
  - Train-test split (70-30).
- *Model Development*:
  - Built using TensorFlow Decision Forests (Random Forest).
  - Out-of-Bag (OOB) evaluation for performance monitoring.
- *Evaluation Metrics*:
  - RMSE (Root Mean Squared Error).
  - Feature importance analysis.
- *Visualization*:
  - Plots for feature distributions and evaluation metrics.

---

## 📊 Dataset
- *Source*: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- *Training Data*: 1460 houses with 79 features.
- *Test Data*: 1459 houses with missing sale prices.
- *Target Variable*: SalePrice (house sale price).

### Example Features:
- *Numerical*: LotArea, GrLivArea, YearBuilt.
- *Categorical*: MSZoning, Neighborhood, HouseStyle.

---

## 🛠 Tools and Technologies
- *Framework*: TensorFlow Decision Forests (TF-DF)
- *Language*: Python
- *Libraries*: 
  - Pandas for data manipulation.
  - Matplotlib for visualizations.
  - Numpy for numerical computations.

---

## ⚙ How to Run the Project
1. Clone the repository:
   bash
   git clone https://github.com/BandaAkshith/House-Prices-Prediction-using-TFDF.git
   
2. Navigate to the project directory:
   bash
   cd House-Price-Prediction-using-TFDF
   
3. Install the required libraries:
   bash
   pip install -r requirements.txt
   
4. Open the Jupyter Notebook:
   bash
   jupyter notebook house-prices-prediction-using-tfdf.ipynb
   
5. Follow the steps in the notebook to load data, train the model, and make predictions.

---

## 📝 Results
- Achieved RMSE of <add your result> on the validation set.
- Feature importance analysis highlighted OverallQual, GrLivArea, and GarageCars as top contributors to house prices.

---

## 📌 Future Improvements
- Experiment with additional models (e.g., Gradient Boosting, XGBoost).
- Optimize hyperparameters for improved accuracy.
- Explore additional feature engineering techniques.

---

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for enhancements or bug fixes.

---

## 🏆 Acknowledgments
- [Kaggle Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) for the data.
- TensorFlow Decision Forests team for their fantastic library.
