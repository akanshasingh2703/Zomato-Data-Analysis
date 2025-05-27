# 🍽️ Zomato Data Analysis Project

This project focuses on uncovering insights from Zomato's food delivery data, which involves over **17.5 million monthly transacting users** and a growing base of **226,000+ restaurant partners**. The analysis uses data visualization and Python-based exploratory data analysis (EDA) to answer key business questions.

---

## 🔍 Objectives

The primary goal is to provide actionable insights for Zomato’s strategic planning by analyzing:

1. Customer ordering preferences by restaurant type
2. Customer engagement through vote counts
3. Rating distributions across restaurants
4. Average order spending by couples
5. Comparison of customer satisfaction between online and offline orders
6. Identifying restaurant types with higher offline order volumes for targeted offers

---

## 📊 Analysis Summary

### ✅ 1. Most Popular Restaurant Type
- Used `countplot` to determine which type of restaurants are ordered from the most.
- Result shows clear trends in customer preference by category.

### ✅ 2. Votes by Restaurant Type
- Aggregated total votes per restaurant type using `groupby` and `sum()`.
- Plotted line chart to visualize customer engagement per category.

### ✅ 3. Rating Distribution
- Created a histogram of restaurant ratings.
- Most ratings are clustered in a specific range, showing typical customer satisfaction levels.

### ✅ 4. Average Couple Spending
- Analyzed the `approx_cost(for two people)` column.
- Used countplot to understand common spending brackets among couples ordering online.

### ✅ 5. Online vs Offline Ratings
- Created a boxplot comparing restaurant ratings for online and offline orders.
- Online mode tends to show better or more consistent ratings.

### ✅ 6. Offline Orders by Restaurant Type
- Built a pivot table and a heatmap to show which restaurant types receive more offline orders.
- Highlights opportunity for Zomato to provide offline discounts or offers in specific categories.

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook** – interactive analysis

---

## 📁 Dataset Description

The dataset includes:
- Restaurant type (`listed_in(type)`)
- Customer votes
- Ratings
- Approximate cost for two people
- Order mode (`online_order`)

Data cleaning included:
- Parsing and converting rating values
- Handling vote and cost formats

---

## 📌 Key Takeaways

- Certain types of restaurants dominate online food orders.
- Votes and ratings reveal customer satisfaction and popularity.
- Couples exhibit consistent spending behavior, which can inform marketing.
- Online orders receive better ratings overall.
- Zomato can optimize offers for restaurants with higher offline traffic.

---

## 📈 Visuals Included

- Bar plots
- Line graphs
- Histograms
- Boxplots
- Heatmaps

These help clearly present trends and support insights with visual evidence.

---

## ✅ Conclusion

This analysis supports data-driven decision-making for Zomato’s food delivery operations. Insights can be used to enhance customer satisfaction, improve restaurant partnerships, and optimize promotional strategies.
