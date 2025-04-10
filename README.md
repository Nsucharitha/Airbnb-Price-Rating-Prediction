# 🏠 Airbnb Price & Rating Predictor

This project predicts the nightly price of an Airbnb listing based on features like the number of bedrooms, bathrooms, minimum nights, availability, reviews, and ratings. It uses machine learning models trained on publicly available Airbnb data and provides an interactive web app built with Streamlit.

---

## 📌 Features

- Predicts **Airbnb listing price** using:
  - Bedrooms, Bathrooms
  - Minimum nights
  - Number of reviews
  - Availability (days/year)
  - Review rating
- Built with **XGBoost Regression**
- Live **Streamlit app** with user-friendly inputs
- Deployed on **Streamlit Cloud**

---

## 📊 Dataset

Data sourced from [Inside Airbnb](http://insideairbnb.com/get-the-data.html).  
Example: [New York City-Albany – listings.csv.gz](http://data.insideairbnb.com/united-states/ny/new-york-city/2024-03-25/data/listings.csv.gz)

---

## 🧠 ML Workflow

1. Data cleaning & preprocessing (handling missing values, one-hot encoding, etc.)
2. Feature selection
3. Model training:
   - Linear Regression
   - Random Forest Regressor
   - **XGBoost Regressor** ✅ (best performer)
4. Model evaluation using:
   - RMSE, MAE, R²
5. Deployment with Streamlit

---

## 🚀 Demo

🌐 Live App: [[Your Streamlit URL here](https://airbnb-price-rating-prediction-ip34gynvesvv5z3fhxm3jz.streamlit.app)]  
🧠 Try it: Enter listing details and get an estimated nightly price.

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- Scikit-learn, XGBoost, Joblib
- Streamlit (for the web interface)
- Matplotlib / Seaborn (EDA)

---

## 📂 Project Structure

