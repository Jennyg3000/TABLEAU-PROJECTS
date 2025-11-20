# Gapminder Health and Demographic Analysis

This repository contains an analysis and visualization project based on the **`GapminderHealth`** dataset. The project explores global health and demographic indicators, providing insights into life expectancy, population trends, and various health metrics using Power BI.

---

## 💾 Data Source

The primary data source for this project is:
* **`GapminderHealth.xlsx - GapminderHealth.csv`**: A comprehensive dataset containing health and demographic statistics from various countries and years.

---

## 📋 Table Details

The dataset consists of records with 13 columns, offering granular data for analysis. The table structure is detailed below:

| Column Name | Data Type | Description |
|:---|:---|:---|
| **Continent** | Text | The geographical continent (e.g., Asia, Europe, Africa). |
| **Country** | Text | The name of the country. |
| **Year** | Integer | The year the data was recorded (e.g., 1990, 2008). |
| **Life Expectancy** | Float | The average life expectancy in years. |
| **Gender** | Text | The recorded gender ('men' or 'women'). |
| **BMI** | Float | Body Mass Index. |
| **Blood Pressure** | Integer | Average blood pressure measurement. |
| **Cholesterol** | Float | Average cholesterol level. |
| **Lung Cancer** | Float | A measure related to lung cancer (e.g., incidence/mortality rate). |
| **Liver Cancer** | Float | A measure related to liver cancer (e.g., incidence/mortality rate). |
| **Stomach Cancer** | Float | A measure related to stomach cancer (e.g., incidence/mortality rate). |
| **Population** | Integer | Total population for the country and gender. |
| **Population Growth** | Float | The annual population growth rate (in percentage). |

---

## 📊 Power BI Visualizations

The Power BI dashboard provides a series of interactive charts to explore the key health trends in the dataset.

### 1. Life Expectancy by Continent (Bar Chart)

* **Chart Type:** **Bar Chart**
* **Dimensions & Measures:** Visualizes the **Average Life Expectancy** (measure) grouped by **Continent** (dimension).
* **Key Insight:** This chart provides a clear, side-by-side comparison of the overall health status across the world's major continents, instantly highlighting regions with the highest and lowest life expectancies.

<img width="1354" height="653" alt="image" src="https://github.com/user-attachments/assets/943b3906-c1c5-4809-853f-a7d33d544e6c" />


### 2. Life Expectancy Trend (Line Chart)

* **Chart Type:** **Line Chart**
* **Dimensions & Measures:** Tracks the **Average Life Expectancy** (measure) over the **Year** (dimension).
* **Key Insight:** This visualization reveals the long-term trends and progression of global health. It shows the rate of change and identifies specific periods where life expectancy saw significant increases or decreases.

<img width="1344" height="656" alt="image" src="https://github.com/user-attachments/assets/bee091f4-ed3d-479d-a811-7017d76a0f58" />

### 3. Population by Gender (Pie Chart)

* **Chart Type:** **Pie Chart**
* **Dimensions & Measures:** Displays the **Total Population** (measure) proportioned by **Gender** (dimension).
* **Key Insight:** Illustrates the population distribution between men and women, helping to understand demographic balance within the dataset.

<img width="1" height="1" alt="image" src="https://github.com/user-attachments/assets/fa5457dc-8d5a-4bc4-8e6c-0778b7345275" />


### 4. Life Expectancy vs BMI (Scatter Chart)

* **Chart Type:** **Scatter Chart**
* **Dimensions & Measures:** Plots **Life Expectancy** (Y-axis) against **BMI** (X-axis).
* **Key Insight:** Used to investigate the correlation between a country's average body mass index and its overall life expectancy. Outliers can be easily identified for further investigation.

<img width="1351" height="655" alt="image" src="https://github.com/user-attachments/assets/715e5f7a-2e33-45b3-98a7-84f8944f61ab" />

### 5. Liver Cancer by Top 5 Country (Packed Bubble Chart)

* **Chart Type:** **Packed Bubble Chart**
* **Dimensions & Measures:** Features the **Top 5 Countries** based on their **Liver Cancer** rate. The size of each bubble corresponds to the magnitude of the Liver Cancer measure.
* **Key Insight:** This highly visual chart immediately draws attention to the countries facing the most critical challenges regarding liver cancer incidence or mortality, allowing analysts to focus on potential regional risk factors.

<img width="1359" height="656" alt="image" src="https://github.com/user-attachments/assets/0a82042b-1c6d-4df1-960b-c9a5afbfd38d" />

