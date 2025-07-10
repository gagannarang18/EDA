# 🍽️ Zomato EDA Project

Exploratory Data Analysis (EDA) on the **Zomato Restaurant Dataset**, enriched with **country codes** to uncover key insights about restaurant ratings, delivery options, and country-wise trends.

---

## 📁 Project Structure

This repository contains:

- `Zomato.csv` — Main dataset containing restaurant-level information.
- `CountryCode.xlsx` — Mapping of country codes to country names.
- `Zomato_EDA.ipynb` — Notebook where all analysis and visualizations are done.
- `README.md` — This file.

---

## 📊 Objective

To perform in-depth EDA on the Zomato dataset and answer questions like:
- Which countries have the highest number of Zomato-listed restaurants?
- How are ratings distributed across different countries and colors?
- Are there restaurants with missing data?
- Which currency is used in which country?
- What delivery or booking options are available country-wise?
- And more...

---

## 🔧 Technologies Used

- **Python 3**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📌 Key Columns in `Zomato.csv`

- `Restaurant ID`
- `Restaurant Name`
- `Country Code`
- `City`
- `Average Cost for two`
- `Currency`
- `Has Table booking`
- `Has Online delivery`
- `Aggregate rating`
- `Rating color`
- `Rating text`

---

## 🔍 Key EDA Steps

- Merged `Zomato.csv` with `CountryCode.xlsx` on `Country Code`
- Checked for missing values
- Plotted rating distributions
- Visualized restaurant counts per country
- Examined the relationship between rating colors and scores
- Analyzed delivery and table booking trends

---

## 📈 Visualizations Created

- Heatmap of missing data
- Bar plots of rating counts vs colors
- Pie chart of restaurants by country
- Country-wise restaurant distribution
- Delivery availability option among countires

---

## 📌 Key Observations

- **India** has the highest number of restaurants on Zomato.
- **White rating color** corresponds to **"Not Rated"**, and makes up a large portion.
- **'Dark Green' color** represents **Excellent** rating (above 4.5).
- Some countries use **unique currencies** like QAR (Qatar), ZAR (South Africa).
- **Online delivery** is primarily supported in India and UAE.
- New Delhi, Gurgaon, Noida, Faridabad, Gaziabad among top cities that uses **Zomato** in **India**

---

## 📂 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/gagannarang18/EDA.git
