# 🔥 Analyzing Wildfire Activities in Australia

This project is a data visualization practice assignment from the IBM Data Science Professional Certificate. It focuses on analyzing and visualizing wildfire activity data in Australia using Python, with libraries such as **Matplotlib**, **Seaborn**, and **Folium**.

The goal is to develop hands-on experience in creating effective and insightful plots that support data-driven storytelling.

---

## 🎯 Objectives

By completing this notebook, you will learn how to:

- Load and explore time-series environmental data.
- Create line plots, bar charts, pie charts, histograms, and scatter plots.
- Use advanced Seaborn features like color encoding and stacked distributions.
- Apply date-time transformations and group-by operations.
- Visualize data over time and by categorical regions.
- Enhance charts with titles, labels, gridlines, and legends.

---

## 📁 Dataset

- **Name:** Historical Wildfires
- **Source:** IBM Skills Network  
  [🔗 Download CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Historical_Wildfires.csv)

- **Key Features:**
  - `Date`: Timestamp of detection
  - `Region`: Geographic region in Australia
  - `Count`: Number of pixels flagged as wildfire
  - `Estimated_fire_area`: Estimated area of fire
  - `Mean_estimated_fire_brightness`: Average brightness of fire detection
  - `Mean_estimated_fire_radiative_power`: Power of detected heat
  - `Mean_confidence`: Confidence level of detection

---

## 📊 Visualizations Included

| Chart Type     | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Line Plot      | Tracks average fire area over years and months                              |
| Bar Chart      | Compares fire brightness by region                                           |
| Pie Chart      | Visualizes the proportion of fire pixel counts by region                    |
| Histogram      | Shows distribution of fire brightness across all observations               |
| Stacked Histogram | Distribution of brightness by region using color hue                    |
| Scatter Plot   | Shows correlation between radiative power and detection confidence          |

---

## 🛠️ Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import folium
```

---

## 🚀 How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/ibm-python-visualization-practice.git
   cd ibm-python-visualization-practice
   ```

2. **Install dependencies**:
   ```bash
   pip install pandas matplotlib seaborn folium requests
   ```

3. **Run the notebook**:
   ```bash
   jupyter notebook M_Elzayat_IBM_Python_Visualization_Practice.ipynb
   ```

---

## 📌 Sample Visuals

Here are a few of the visual insights from the notebook:

- 📈 **Average Fire Area Over Time**
- 📊 **Mean Fire Brightness by Region**
- 🥧 **Pie Chart of Fire Counts by Region**
- 📉 **Fire Brightness Distribution Histogram**
- 🔬 **Scatter Plot: Radiative Power vs Confidence**

---

## 👤 Author

**Mahmoud Mohamed Elzayat**  
Data Analyst | Python & Power BI  
📍 [LinkedIn](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)  

---

> ⚠️ Disclaimer: This project is for educational purposes only and based on open datasets provided by IBM Skills Network.
