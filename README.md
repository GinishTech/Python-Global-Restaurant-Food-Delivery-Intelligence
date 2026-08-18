## 🍽️ Python Global Restaurant & Food Delivery Intelligence
An end-to-end Exploratory Data Analysis project on a global food delivery market dataset — covering 5,000 restaurants, 62K+ menu items, and delivery performance across 10 cities in 5 countries.

## 📊 Project Overview

This project explores relationships between geography, pricing, nutrition, restaurant amenities, and delivery performance in the food delivery space using Python. It includes city-level market comparisons, cuisine trends, menu/nutrition analysis, delivery reliability metrics, and pricing dynamics over time.

***11 relational datasets, 161,945 total rows:***

| Dataset | Description | Rows |
|---|---|---|
| `restaurants.csv` | Core restaurant info (cuisine, rating, price level, status) | 5,000 |
| `restaurant_features.csv` | Amenities (WiFi, outdoor seating, parking, etc.) | 5,000 |
| `restaurant_statistics.csv` | Popularity & value scores | 5,000 |
| `delivery_metrics.csv` | Delivery time, fees, cancellation rate | 3,187 |
| `menus.csv` | Menu items, price, category | 62,417 |
| `nutrition.csv` | Calories, protein, fat, carbs, sugar, sodium per item | 62,417 |
| `price_history.csv` | Price change events over time | 18,887 |
| `cities.csv` / `city_statistics.csv` | City demographics & market metrics | 10 |
| `countries.csv` | Country-level context | 5 |
| `cuisines.csv` | Cuisine taxonomy & region mapping | 12 |

**Import Libraries & Color Visualization**
<img width="800" height="550" alt="1" src="https://github.com/user-attachments/assets/3da9c2f8-8b5a-4406-85fa-f42a2574fa9f" />

## 🛠️ Tech Stack

- **Python** — pandas, numpy
- **Visualization** — matplotlib, seaborn, plotly
- **Environment** — Jupyter Notebook


**Nutrition Correlation Heatmap**
<img width="800" height="480" alt="2" src="https://github.com/user-attachments/assets/61b064b1-3675-4919-b622-47a6ad2e486e" />


**Countries By Region**

<img width="706" height="550" alt="4" src="https://github.com/user-attachments/assets/3d13209c-6064-4f7c-bc9d-40de6d1fdcf1" />


**Cumulative Restaurants**

<img width="750" height="438" alt="3" src="https://github.com/user-attachments/assets/c3b3fb39-72dc-4b8f-bf7a-40277eb5b0a1" />




## 🗺️ Global Reach
We didn't just focus on one city. This dataset captures the economic diversity of the globe:
- **North America**: New York City, Los Angeles (High urban density, premium delivery fees)
- **Europe**: London, Manchester (Varying cost of living and cuisine diversity)
- **Asia**: Tokyo, Osaka, Mumbai, Delhi (Hyper-dense logistics, high volume, dynamic peak multipliers)
- **South America**: Sao Paulo, Rio de Janeiro (Emerging market dynamics, unique price histories)

## 🔍 Key Insights

- Restaurant ratings and menu pricing vary meaningfully by city, correlating more with cost-of-living than with rating quality.
- Certain amenities (e.g. outdoor seating, WiFi) show a measurable positive lift in average restaurant rating.
- Menu item pricing and calorie content vary significantly by food category; vegetarian items differ from non-vegetarian items in average nutrition profile.
- A meaningful share of deliveries run later than their estimated time, and cancellation rates vary widely across restaurants.
- Popularity score and star rating are correlated but not identical — value and consistency also drive popularity.

## 📌 Author
Ginish Kumar — [LinkedIn](https://linkedin.com/in/ginish-kumar-544b2a1b4)

[GitHub](https://github.com/GinishTech) 





