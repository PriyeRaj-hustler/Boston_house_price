# 🏠 Boston House Price Prediction

This project predicts housing prices in Boston using machine learning techniques. The dataset contains information about various factors that influence house prices such as crime rate, number of rooms, distance to employment centers, and more.

## 🔍 Overview

- **Goal**: Predict the median value of owner-occupied homes.
- **Dataset**: Boston Housing Dataset (13 features).
- **Model Used**: Linear Regression
- **Evaluation Metrics**: MSE, RMSE, R² Score

## 📊 Features in the Dataset

- CRIM — per capita crime rate by town
- ZN — proportion of residential land zoned for large lots
- INDUS — proportion of non-retail business acres per town
- CHAS — Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX — nitric oxides concentration
- RM — average number of rooms per dwelling
- AGE — proportion of owner-occupied units built before 1940
- DIS — weighted distances to five Boston employment centers
- RAD — index of accessibility to radial highways
- TAX — full-value property tax rate
- PTRATIO — pupil-teacher ratio
- B — proportion of African American residents
- LSTAT — % lower status of the population

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab

## 📈 Model Training and Evaluation

- **Preprocessing**:
  - Data cleaning
  - Feature scaling (StandardScaler)
- **Model**:
  - Linear Regression using `scikit-learn`
- **Evaluation**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

## 📎 Demo Notebook

You can explore the full implementation here:  
🔗 [Google Colab - Boston House Price Prediction](https://colab.research.google.com/drive/1BDQcQK53mE6ikkImHjFOcdyskybFl5m3)

## 📌 Results

- Achieved a decent R² score indicating that the linear regression model fits well.
- Visualized predicted vs actual values and residuals for better understanding.

## 📝 Future Improvements

- Try more advanced models (Random Forest, XGBoost, etc.)
- Perform hyperparameter tuning
- Use cross-validation
- Deploy using Flask or Streamlit

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repo and submit a pull request.

## 📬 Contact

For queries or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/priye-raj) or email: priyer_ug_22@ee.nits.ac.in

---

⭐ Star this repository if you found it helpful!
