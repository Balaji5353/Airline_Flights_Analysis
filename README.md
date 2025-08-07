# 📊✈️ Airline Flights Analysis


<img src="https://i.ytimg.com/vi/gu3Ot78j_Gc/hq720.jpg?sqp=-oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLB-wQbFnzn-oUjliniQatcf6irdjw" width=800>


## Project Link🔗

[Airline Flights  Analysis](Airline_Flights_Analysis.ipynb)


---

## 🎯 Overview

Briefly explain what the project is and why it was undertaken. For example: “This project explores the XYZ dataset to uncover patterns in ABC using Python with NumPy, Pandas, Matplotlib, and Seaborn.”:contentReference[oaicite:1]{index=1}

---

## 📌 Project Goal

- What problem are you addressing?
- What insights are you trying to generate?
- What decisions could be informed by your results?

---

## 🧰 Tools & Technologies

- *Python* 
- *NumPy* – numerical operations
- *Pandas* – data cleaning/manipulation
- *Matplotlib & Seaborn* – visualizations
- List other dependencies or environment files (e.g., requirements.txt, environment.yml).:contentReference[oaicite:2]{index=2}

---

## ✨ Features

- Automatic data cleaning steps: handling missing values, type conversions, renaming columns, feature engineering.
- Exploratory Data Analysis including:
  - Descriptive statistics (mean, median, std) via NumPy and Pandas
  - Histograms + KDE, boxplots, scatterplots, correlation heatmaps
- Optional: time‑series or group‑based visualizations

---

## 🧼 Data Source & Processing

- *Dataset origin*: Describe the data source, URL, license, or citation.
- *Columns description*: List major columns with meaning/types.
- *Cleaning steps*: e.g., "Removed columns with >30% missing, imputed median for numeric fields, coerced dates, standardized names".:contentReference[oaicite:3]{index=3}

---

## 🧭 Insights
## 1. Dataset Overview
- Rows: 300,153 flight records.

- Columns (Key): airline, flight, source_city, destination_city, departure/arrival times, stops, class, duration (in hours), days_left (until departure), price.

## 2. Price Analysis
- Average price: ₹20,890

- Price range: ₹1,105 (min) to ₹123,071 (max)

- Price percentiles:

- 25th percentile: ₹4,783

- 50th percentile (Median): ₹7,425

- 75th percentile: ₹42,521

## 3. Flight Duration
- Average duration: 12.22 hours (but ~0.83hr for direct, short-haul routes)

- Min duration: 0.83hr (e.g., Bangalore ↔ Chennai by Indigo, direct flights)

- Max duration: 49.83hr (likely multi-stop itineraries)

## 4. Popular and Efficient Routes
- Bangalore – Chennai (and vice versa) by Indigo (night, direct):

- Consistent duration: 0.83hr

- Economy fare drops over time (example: from ₹3,498 to under ₹1,604 as days_left increases).

- Delhi – Mumbai (multiple airlines, direct):

- Duration: ~2.2hr

- Economy fares cluster around ₹5,950 when booked with 1 day left.

- Chennai – Hyderabad (Vistara, Business):

- Duration: 10–14hr (likely indirect), price >₹69,000 for last-minute, business class.

## 5. Time and Price Dynamics
- Advance booking trend:
- For short-haul direct routes (e.g., Indigo, Bangalore ↔ Chennai), prices decrease sharply as days_left increases up to a point, but then stabilize.

## 6. Class and Stop Insights
- Economy fares: Affordable, peak competition among low-cost carriers.

- Business fares: Steeply higher, with last-minute business tickets exceeding ₹80,000 on some long or multi-stop routes (e.g., Chennai–Hyderabad).

- Stops: Direct flights have much shorter duration and cheaper fares. Multi-stop itineraries surge in both price and travel time

---

## 💡 Recommendations

Based on the insights, suggest actions or business decisions such as:

- Focus marketing toward group A
- Explore further features to predict Y
- Automate repeated analysis in production.

---
