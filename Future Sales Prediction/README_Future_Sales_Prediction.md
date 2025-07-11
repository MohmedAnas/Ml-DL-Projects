# 📈 Future Sales Prediction Model

This project demonstrates a simple yet effective **Machine Learning model** that predicts product sales based on advertising spending across **TV**, **Radio**, and **Newspaper**. The dataset used is the classic `advertising.csv`, which contains real-world inspired ad budget and sales figures.

## 🔍 Overview

We explore how different advertising media affect product sales using **Linear Regression**. Visualizations are created using **Plotly** to show relationships between features and sales.

## 📂 Dataset

- `TV`: Advertising dollars spent on TV.
- `Radio`: Advertising dollars spent on Radio.
- `Newspaper`: Advertising dollars spent on Newspaper.
- `Sales`: The number of units sold.

## 📊 Visualizations

The following relationships were plotted:
- Sales vs TV Spend
- Sales vs Radio Spend
- Sales vs Newspaper Spend

## 🧠 ML Model

- Model: `LinearRegression()` from `sklearn`
- Train/Test Split: 80% train, 20% test
- Performance metric: `R² Score`
- Model Input: `TV`, `Radio`, and `Newspaper` spend values
- Model Output: Predicted `Sales`

## 🧪 Sample Prediction

```python
# Sample Input (TV, Radio, Newspaper)
features = np.array([[230.1, 37.8, 69.2]])
predicted_sales = model.predict(features)
```

## 📦 Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `plotly`

## 📁 File Structure

```
advertising.csv
sales_prediction_model.ipynb / .py
README.md
```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

✨ Stay tuned for more ML projects!