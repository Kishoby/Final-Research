# ✅ **Summary of Correlation**

Correlation measures how strongly one variable is related to another.

### ✔ Positive Correlation (+)

When one value increases, the other also increases.
Example: If **PM10 increases**, PM2.5 also increases.

### ✔ Negative Correlation (–)

When one value increases, the other decreases.
Example: If **visibility decreases**, PM2.5 increases (air becomes more polluted).

### ✔ Strength of Correlation

The **absolute value** determines importance:

* |80%| = very strong
* |50%| = strong
* |20%| = moderate
* |5%| = weak

Both **positive and negative** correlations help the model learn patterns.

---

# 🎯 **Why These Top 15 Features Are Suitable for Predicting PM2.5**

The top 15 features were selected based on the **highest absolute correlation** with PM2.5. These are the features that show the **strongest statistical relationship** with PM2.5 either directly (positive) or inversely (negative).

### ✔ 1. Strong Pollution Indicators

Features like:

* **air_quality_us-epa-index**
* **air_quality_gb-defra-index**
* **air_quality_PM10**
* **Carbon Monoxide**, **Nitrogen Dioxide**, **Sulphur Dioxide**

These pollutants often increase together with PM2.5 because they come from similar sources (traffic, industry, combustion).

### ✔ 2. Weather Factors Affecting PM2.5

Features like:

* **humidity**
* **cloud**
* **visibility_km**
* **visibility_miles**
* **wind_degree**
* **precip_mm**, **precip_in**
* **gust_kph**

These influence how particles travel, settle, or disperse in the air:

* **Low visibility** usually indicates high particulate matter.
* **High humidity** can make PM2.5 stick to the air.
* **Wind** carries particles away or brings new pollutants.
* **Rain (precip_mm)** clears dust from the air.

These weather-related variables impact pollution concentration levels, giving the model important signals.

### ✔ 3. Location-Based Influence

* **longitude**, **latitude**

Geographical position affects surrounding pollution sources (traffic, urban area, industrial zones).

### ✔ 4. Time-Based Influence

* **last_updated_epoch**

Pollution levels vary with time of day, season, and weather cycles.

---

# ⭐ **Conclusion**

These **Top 15 features** have the strongest measurable relationship with PM2.5 levels.
They include:

* Pollution indicators
* Weather conditions
* Geographic and temporal factors

Because they influence or reflect how fine dust behaves in the environment, they significantly improve prediction performance for **Random Forest, XGBoost, Linear Regression, and CNN models**.


