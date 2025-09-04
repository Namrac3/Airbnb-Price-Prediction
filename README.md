# 🏡 Predict Airbnb Prices in Sydney

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![ML](https://img.shields.io/badge/ML-Regression-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview
This project predicts **Airbnb rental prices in Sydney** using **machine learning**.  
It covers the complete pipeline from **data cleaning → feature engineering → modeling → evaluation**.

✨ Key highlights:
- ✅ Comprehensive **EDA** (exploratory data analysis)  
- ✅ Feature selection & preprocessing  
- ✅ Model building (Regression-based approaches)  
- ✅ Insights on pricing factors  

---

## 📂 Repository Structure
```
Predict-Airbnb-Prices-Sydney/
│
├── notebooks/
│   └── Case_Study_1_Predict_Airbnb_Prices_Sydney.ipynb
│
└── README.md
```

---

## 📊 Dataset
The dataset used in this project is available on **[Inside Airbnb](http://insideairbnb.com/get-the-data.html)**.  

👉 Please download the **Sydney listings dataset** from the website and place it in a `data/` folder before running the notebook.

**Dataset Features include:**
| Feature                | Description |
|-------------------------|-------------|
| `id`                   | Unique identifier for listing |
| `name`                 | Title of the listing |
| `host_id`              | Unique ID of the host |
| `neighbourhood`        | Location of the property |
| `room_type`            | Type of accommodation (Entire home, Private room, etc.) |
| `price`                | Target variable (rental price per night) |
| `minimum_nights`       | Minimum stay requirement |
| `number_of_reviews`    | Popularity of listing |
| `availability_365`     | Number of days available in a year |

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Predict-Airbnb-Prices-Sydney.git
   cd Predict-Airbnb-Prices-Sydney
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/Case_Study_1_Predict_Airbnb_Prices_Sydney.ipynb
   ```

---

## 📈 Methodology
🔎 **Step 1: Data Cleaning** → Handle missing values, outliers, and formatting.  
📊 **Step 2: Exploratory Data Analysis** → Visualize distributions & correlations.  
🛠️ **Step 3: Feature Engineering** → Encode categorical features & scale numeric features.  
🤖 **Step 4: Modeling** → Apply regression models and evaluate results.  
📉 **Step 5: Evaluation** → Use RMSE, R², and MAE for performance metrics.  

---

## 📊 Sample Visualizations
*(These will render if you add screenshots from your notebook)*  

| Correlation Heatmap | Price Distribution |
|---------------------|--------------------|
| ![heatmap](images/heatmap.png) | ![distribution](images/price_dist.png) |

---

## ✅ Results & Insights
- 📌 **Location** and **room type** are the most significant predictors of price.  
- 📌 Certain neighborhoods command higher prices consistently.  
- 📌 The baseline regression model shows strong predictive power.  

---

## 🔮 Future Improvements
- 🚀 Experiment with advanced models like **XGBoost, CatBoost, Random Forests**.  
- 🌍 Integrate **geospatial analysis** (distance to landmarks, transport).  
- 🖥️ Build a **web app** (Streamlit/Flask) for interactive predictions.  

---

## ✨ Author
👩‍💻 Developed by **Namrata Chavan**  
🔗 [GitHub Profile](https://github.com/your-username)

