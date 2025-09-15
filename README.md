# 📈 Airbnb Data Analysis: A Case Study in New York City

This repository contains the code and resources for a data analysis project focused on the Airbnb market in New York City. The project leverages Python and Power BI to transform raw data into actionable insights for potential investors and hosts.

---

### 🎯 Project Goals

The primary objective of this analysis was to answer the following key business questions:

-   **What is the overall size and average price of the New York Airbnb market?**
-   **How are Airbnb listings distributed geographically across different boroughs?**
-   **What are the key factors influencing pricing?**
-   **Can we identify any significant correlations between variables?**

---

### 🚀 Methodology

The project followed a structured data analysis workflow, broken down into two main phases:

#### **1. Data Processing & Analysis (Python)**

-   **Data Acquisition:** The dataset was sourced from the **Airbnb Open Data** on Kaggle.
-   **Data Cleaning:** Using the **Pandas** library, the raw data was cleaned to handle missing values, correct data types, and remove outliers.
-   **Exploratory Data Analysis (EDA):** A correlation matrix and a heatmap were generated using **Matplotlib** and **Seaborn** to explore relationships between key numerical variables.

#### **2. Visualization & Reporting (Power BI)**

-   The cleaned dataset was imported into **Power BI** to create a dynamic and interactive dashboard.
-   The dashboard includes visualizations and KPIs that answer the core project questions, such as:
    -   Average Price per night
    -   Total number of listings
    -   Price distribution by borough and room type

---

### 📊 Key Findings

The analysis revealed several important insights into the New York Airbnb market:

-   **Market Overview:** The market is large and dynamic, with **over 48,600** total listings. The average nightly price is approximately **$140**.
-   **Geographic Distribution:** Listing density is significantly higher in **Manhattan** and **Brooklyn**, indicating strong market demand.
-   **Pricing Drivers:** **Room type** is a major factor affecting price. Listings for an **"Entire home/apt"** are priced substantially higher on average than private or shared rooms.
-   **Correlation:** No strong linear correlation was found between price and other numerical variables in the dataset. This suggests that pricing is a **complex, multi-faceted process** influenced by numerous factors not present in the dataset.

---

### 💡 Recommendations for Future Analysis

To gain a deeper understanding of the market and build a more accurate predictive model, we recommend that future analysis includes:

-   **Seasonal and Temporal Data:** Incorporate data on different seasons, holidays, and special events to identify seasonal pricing patterns.
-   **Listing Amenities:** Collect data on amenities such as pools, Wi-Fi, parking, and the number of bedrooms.
-   **Location Accessibility:** Analyze the impact of a listing's proximity to public transit, shopping centers, restaurants, and tourist attractions on its price.

---

### 🛠️ Tools & Technologies

-   **Python:** For data cleaning, analysis, and processing.
-   **Pandas & NumPy:** The core libraries for data manipulation and numerical operations.
-   **Matplotlib & Seaborn:** For creating visualizations during the EDA phase.
-   **Power BI:** For building the final interactive dashboard and report.
-   **Jupyter Notebook:** The primary environment for writing and running the code.

---

### 📋 How to Use

To replicate this project, simply download the `AB_NYC_2019.csv` file from Kaggle and run the Python code provided in the Jupyter Notebook to clean the data. Then, import the cleaned CSV file into Power BI to create your own visualizations.
