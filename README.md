# 🌍India Air Pollution Analysis – Power BI Dashboard

## 📊 Project Overview

**India Environmental Risk Overview** is an interactive **Power BI dashboard** developed to analyze and visualize historical air pollution data across different locations in India.

The dashboard helps users understand pollution patterns, compare major pollutants, identify areas with higher pollution levels, and analyze changes over time.

The main pollutants analyzed are:

* **SO₂** – Sulfur Dioxide
* **NO₂** – Nitrogen Dioxide
* **RSPM** – Respirable Suspended Particulate Matter
* **SPM** – Suspended Particulate Matter

## The dataset contains observations from different Indian states and cities, including locations such as Delhi, Raipur, Ahmedabad, Guwahati, Hyderabad and others.

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze historical air pollution levels across India.
2. Compare different pollutants such as SO₂, NO₂, RSPM and SPM.
3. Identify pollution trends over different years.
4. Compare pollution levels between different states and locations.
5. Understand seasonal variations in pollution.
6. Provide an interactive dashboard for easier data analysis.
7. Help users identify areas with relatively higher pollution levels.

---

## 🗂️ Dataset

The dataset contains historical air-quality observations with information including:

| Column / Information | Description                              |
| -------------------- | ---------------------------------------- |
| Date                 | Date of observation                      |
| Year                 | Year of observation                      |
| Month                | Month of observation                     |
| Season               | Summer, Monsoon, Post-Monsoon or Winter  |
| State                | Indian state                             |
| Location             | City/location                            |
| Monitoring Agency    | Organization responsible for monitoring  |
| Area Type            | Industrial, Residential, Sensitive, etc. |
| SO₂                  | Sulfur dioxide concentration             |
| NO₂                  | Nitrogen dioxide concentration           |
| RSPM                 | Respirable suspended particulate matter  |
| SPM                  | Suspended particulate matter             |

The data includes seasonal categories such as **Summer, Monsoon, Post-Monsoon and Winter**.

---

## 📈 Power BI Dashboard

The dashboard provides an interactive view of India's historical pollution landscape.

### Key Performance Indicators (KPIs)

The dashboard includes KPI cards for:

* **Total Records**
* **Total Locations**
* **Total States**
* **Average SO₂**
* **Average NO₂**

### 📊 Dashboard Visualizations

The dashboard contains:

#### 1. Pollution Overview

Provides an overall summary of the pollution dataset.

#### 2. Pollution Map

Displays pollution information geographically across different locations.

#### 3. Long-Term Pollution Trend

A line chart is used to analyze how pollution levels change over the years.

#### 4. Major Pollutant Comparison

A bar chart compares the major pollutants:

**SO₂ vs NO₂ vs RSPM vs SPM**

#### 5. Scatter Chart

Used to analyze the relationship between different pollution measurements.

#### 6. Decomposition Tree

Used to explore pollution values by dimensions such as state, location, year and other categories.

---

## 🔎 Important Insights

### RSPM

RSPM represents **Respirable Suspended Particulate Matter**.

Higher RSPM values generally indicate a greater concentration of particulate matter in the air and therefore a higher particulate pollution level.

For example, the dataset contains observations with RSPM values above 600 in some locations and periods.

### Seasonal Analysis

The dataset allows pollution to be analyzed across:

* Summer
* Monsoon
* Post-Monsoon
* Winter

This makes it possible to investigate how pollution levels vary across different seasons.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Cleaning & Transformation**
* **Data Visualization**
* **Git & GitHub**

---

## 📁 Project Structure

```text
AirPollutionReport/
│
├── definition.pbir
├── definition/
│   ├── pages/
│   └── ...
│
├── StaticResources/
│   ├── RegisteredResources/
│   └── SharedResources/
│
├── .platform
└── README.md
```

The Power BI project is stored in **PBIP (Power BI Project)** format, allowing the report definition and resources to be maintained as files and version-controlled using Git.

---

## 💡 Key Features

* Interactive Power BI dashboard
* Historical pollution analysis
* State and location comparison
* Year-wise pollution trends
* Seasonal analysis
* Pollutant comparison
* Interactive filters
* KPI cards
* Geographic visualization
* Data-driven insights

---

## 🚀 How to Use

1. Clone this repository.
2. Open the Power BI project in **Power BI Desktop**.
3. Open the Power BI project/report files.
4. Refresh the data if required.
5. Use the dashboard filters to explore:

   * Year
   * State
   * Location
   * Season
   * Pollutant
6. Interact with the charts and visuals to analyze pollution patterns.

---

## 📌 Project Outcome

This project demonstrates how **Power BI can be used to transform historical environmental data into an interactive analytical dashboard**.

It provides a simple way to explore pollution patterns across Indian locations and understand changes in major pollutants over time.

---

## 👨‍💻 Author

**Ajay**

### Project: India Air Pollution Analysis

**Technology:** Microsoft Power BI

**Domain:** Data Analytics / Environmental Data Analysis

---

## ⭐ Future Improvements

Future versions of the project could include:

* Real-time air-quality data
* PM2.5 and PM10 analysis
* AQI calculation
* More advanced geographical analysis
* Automated data refresh
* Forecasting future pollution levels
* Machine Learning-based pollution prediction
* Additional environmental indicators
