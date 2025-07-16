
# 📱 Instagram Insights & Impressions Analysis + Predictive Model

This project analyzes **Instagram post insights** (likes, comments, shares, impressions, etc.) and builds a **regression model** to predict total **impressions** based on engagement metrics. It uses data visualization and machine learning to understand and predict what drives Instagram reach.

---

## 📁 Dataset

- File: `Instagram.csv`
- Key Columns:
  - `Caption`
  - `Likes`, `Comments`, `Shares`, `Saves`, `Follows`
  - `Profile Visits`, `Impressions`
  - `From Home`, `From Hashtags`, `From Explore`, `From Other`

---

## 🚀 Technologies Used

- **Python 3**
- **pandas**, **numpy** – data processing
- **matplotlib**, **seaborn**, **plotly** – visualizations
- **wordcloud** – content analysis
- **scikit-learn** – regression modeling
- **PassiveAggressiveRegressor** – used to predict impressions
- **statsmodels** – regression trendlines in scatter plots

---

## 📊 Key Visualizations

- Distributions of impressions from different sources: Home, Hashtags, Explore, Other
- Pie chart showing contribution of each source
- WordCloud generated from post captions
- Scatter plots:
  - Impressions vs Likes
  - Impressions vs Comments
  - Impressions vs Shares

---

## 📈 Predictive Modeling

A **Passive Aggressive Regressor** is trained to predict **total impressions** based on:

- Likes
- Saves
- Comments
- Shares
- Profile Visits
- Follows

### 🧪 Sample Prediction:

```python
features = np.array([[282.0, 233.0, 4.0, 9.0, 165.0, 54.0]])
model.predict(features)
```

---

## 📌 How to Run

1. Clone this repository and place `Instagram.csv` in the working directory.
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn wordcloud
```

3. Run the notebook or Python script to explore visuals and make predictions.

---

## 📎 Author

**Mohmed Anas Ranavdiya**  
Email: anasranawadiya123@gmail.com  
GitHub: [MohmedAnas](https://github.com/MohmedAnas)

---

## 🧠 Use Case

- Understand what drives Instagram post impressions
- Forecast post performance before publishing
- Visualize which source contributes most to your reach
