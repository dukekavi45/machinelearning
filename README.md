# 🍽️ Restaurant Rating Prediction using Machine Learning

This project aims to predict restaurant ratings based on various features like location, cuisines, cost, and other metadata. Using Python and machine learning techniques, we analyze and model the data to make accurate predictions.

## 📌 Project Overview

- **Goal:** Predict restaurant ratings using a machine learning regression model.
- **Dataset:** A CSV file (`Dataset.csv`) containing restaurant information (name, location, cuisines, cost, etc.)
- **Model Used:** Random Forest Regressor
- **Tools & Libraries:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 📂 Project Structure

```bash
Restaurant-Rating-Prediction/
│
├── resturant prediction.py   # Main code for training and prediction
├── Dataset.csv               # Dataset file with restaurant information
├── README.md                 # Project documentation
└── ...
##sample output
plt.scatter(y_test, y_pred)
plt.xlabel("Actual Ratings")
plt.ylabel("Predicted Ratings")
plt.title("Actual vs Predicted Restaurant Ratings")
plt.show()
