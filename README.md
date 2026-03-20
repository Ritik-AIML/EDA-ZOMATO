# EDA-ZOMATO
Here I performed EDA on Zomato's data 

 📌 About This Project

I worked on this project to explore the Zomato dataset and understand what actually makes a restaurant popular in a city like Bengaluru.

Instead of just running models, the main focus was to **dig into the data**, clean it properly, and uncover real patterns—like whether online delivery affects ratings, which locations perform best, and how pricing impacts customer perception.

---

## 📂 What’s in the Dataset?

The dataset includes details about restaurants such as:

* Name and location
* Whether they offer online delivery
* Table booking availability
* Ratings and votes
* Approximate cost for two people
* Type of restaurant and services

---

## 🧹 Data Cleaning (The Real Work)

Before any analysis, the dataset needed serious cleanup:

* Removed columns that didn’t add value
* Renamed columns to make them easier to understand
* Dropped duplicate entries
* Cleaned messy fields like ratings and cost
* Removed missing values
* Applied a few extra transformations wherever needed

This step was important because messy data can completely distort results.

---

## 📊 What I Explored

### 🔹 Services & Features

* Do restaurants with **online delivery** perform better?
* Does **table booking** impact ratings?
* Comparing **table booking vs ratings**

### 📍 Location Matters

* Which locations have the **best-rated restaurants**
* How ratings vary across different areas
* Number of restaurants in each location

### 🍴 Restaurant Patterns

* Different **types of restaurants**
* Types of services offered
* Relationship between **restaurant type and ratings**
* Most popular restaurant chains in Bengaluru

### 📈 Other Observations

* Distribution of ratings (Gaussian trends)
* Cost patterns across restaurants

---

## 📉 Visualizations

I used different plots to make the data easier to understand:

* Bar charts for comparisons
* Count plots for distributions
* Scatter plots for relationships
* Heatmaps for deeper patterns

The idea was simple: **see the story in the data instead of guessing it.**

---

## 🤖 Regression Models

After exploring the data, I tried predicting restaurant ratings using:

### 1. Linear Regression

A basic model to understand simple relationships

### 2. Decision Tree Regression

Helps capture non-linear patterns

### 3. Random Forest Regression

More powerful and generally gave better performance

---

## ⚙️ Tools & Libraries

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 📌 Key Takeaways

* Online delivery and table booking do have an influence on ratings
* Some locations clearly outperform others
* Expensive restaurants are not always the highest rated
* Popular chains dominate multiple areas
* Random Forest worked best among the models

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/zomato-eda.git
cd zomato-eda
pip install -r requirements.txt
jupyter notebook
```

---

## 📁 Project Structure

```
data/           → dataset  
notebooks/      → EDA work  
models/         → regression models  
README.md       → project description  
```

---

## 🎯 What Can Be Improved

* Try advanced models like XGBoost
* Build a dashboard (Streamlit/Power BI)
* Add review sentiment analysis
* Make the project more interactive

