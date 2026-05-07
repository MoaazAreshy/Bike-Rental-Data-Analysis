تمام 👌 ده **README مرتب واحترافي أكثر** وفيه توضيح واضح لتأثير الطقس ودرجة الحرارة وworking days بشكل أقوى:

---

# 🚲 Bike Rental Data Analysis

## 📌 Project Overview

This project analyzes a bike rental dataset to understand the key factors that affect bike demand.
The analysis is performed **using Python only**, focusing on Exploratory Data Analysis (EDA) and data visualization.

The main goal is to uncover how **weather conditions, temperature, and working days** influence user behavior and total bike rentals.

---

## 🧠 Objectives

* Understand dataset structure and features
* Analyze user behavior (casual vs registered users)
* Study the effect of:

  * 🌤️ Weather conditions
  * 🌡️ Temperature and humidity
  * 🌬️ Windspeed
  * 📅 Working days vs weekends
  * 🌦️ Seasonal changes
* Identify patterns and trends in bike demand
* Extract business insights from real-world data

---

## 🛠️ Tools & Libraries

This project is built using **Python only**:

* **Pandas** → Data manipulation and analysis
* **NumPy** → Numerical computations
* **Matplotlib** → Data visualization
* **Seaborn** → Advanced statistical plots

---

## 📊 Key Analyses Performed

* Distribution of total bike rentals (`cnt`)
* Comparison between **casual vs registered users**
* Seasonal analysis of bike usage
* Impact of **weather conditions on demand**
* Effect of **temperature and humidity on rentals**
* Working days vs weekends comparison
* Correlation analysis between numerical features
* Time series analysis of rental trends

---

## 📈 Key Insights

* 🚴‍♂️ Registered users contribute the majority of total bike rentals
* 🌡️ Higher temperatures generally lead to increased bike usage
* 🌧️ Bad weather conditions (rain, mist) significantly reduce demand
* 📅 Working days show more stable and commuter-driven usage patterns
* 🎉 Weekends show more variation and occasional spikes in rentals
* 🌍 Seasonal changes strongly impact overall rental behavior

---

## 📁 Project Structure

```
Bike_Rental_Data_Analysis/
│
├── notebook.ipynb        # Main analysis notebook
├── day.csv               # Dataset
├── README.md             # Project documentation
└── images/             
```

---

## 🚀 How to Run the Project

📦 Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

📥 Import libraries:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

📂 Load dataset:

```python
df = pd.read_csv("day.csv")
```

▶️ Then start exploring the data using EDA and visualization techniques.

---

## 📌 Notes

* This project focuses on **Exploratory Data Analysis (EDA)** only
* No machine learning models were used
* The analysis helps understand real-world transportation demand patterns

---

## 👨‍💻 Author

**Moaz Alii**
Python Data Analysis Project 🚲📊
Built for learning and portfolio purposes
قولّي 👍
