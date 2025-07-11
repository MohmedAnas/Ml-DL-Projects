# 🧾 Waiter Tips Prediction Model

This project uses a linear regression model to predict the tips given to waiters based on various features such as:
- Total bill amount
- Gender of the customer
- Smoker status
- Day of the week
- Time of day (Lunch/Dinner)
- Party size

## 📊 Dataset
The dataset used is the classic `tips.csv` dataset available in Seaborn. It includes details of over 200 restaurant bills and tips.

## 🔧 Features Used
| Feature       | Description                    |
|---------------|--------------------------------|
| total_bill    | Total amount of the bill       |
| sex           | Gender of the customer (0=Female, 1=Male) |
| smoker        | Whether the customer smokes (0=No, 1=Yes) |
| day           | Day of the week (0=Thur, 1=Fri, 2=Sat, 3=Sun) |
| time          | Time of day (0=Lunch, 1=Dinner) |
| size          | Size of the dining party       |

## 🧠 Model
We use **Linear Regression** from Scikit-Learn to train the model. The target variable is `tip`, and the input features are those listed above.

## 📈 Visualization
The project uses `Plotly` for:
- Scatter plots with OLS trendlines based on different categorical features.
- Pie charts representing tip distribution based on day, time, gender, and smoker status.

## 🛠️ Tech Stack
- Python
- Pandas & NumPy
- Plotly
- Scikit-learn

## 🔮 Prediction Example
```python
# Predicting tip for:
# total_bill = 24.75, Male, Non-smoker, Thursday, Dinner, size = 4
feature = np.array([[24.75, 1, 0, 0, 1, 4]])
predicted_tip = model.predict(feature)
```

## 📁 File Structure
```
waiter-tips-prediction/
│
├── tips.csv
├── model.py
├── README.md
└── visualizations.ipynb
```

## 🚀 Future Work
- Add more regression models (Random Forest, XGBoost)
- Deploy using Streamlit or Flask for real-time predictions
- Train with a larger dataset for improved accuracy

---

📌 **Author:** Your Name  
📬 **Contact:** your.email@example.com
