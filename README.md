# 🚗 Avito Vehicle Market Analysis Dashboard

## 📌 Project Overview

This project is an interactive **Power BI dashboard** built to analyze the Moroccan vehicle market using data collected from **Avito** advertisements.

The dashboard provides insights into vehicle prices, brands, fuel types, transmission types, manufacturing years, and cities. It helps users understand market trends and compare different vehicle characteristics through interactive visualizations.

---

## 🎯 Objectives

* Analyze the Moroccan used vehicle market.
* Identify the most popular vehicle brands.
* Compare average prices across brands.
* Analyze vehicle prices according to manufacturing year.
* Study the distribution of fuel types and transmission types.
* Provide an interactive dashboard for filtering and exploration.

---

## 📊 Dashboard Features

### KPI Cards

* 🚗 Average Vehicle Age
* 💰 Average Price
* 🏷️ Number of Brands
* ⛽ Number of Fuel Types
* 📈 Maximum Price
* 🔧 Average Manual Vehicle Price

---

### Visualizations

* Number of advertisements by brand
* Average price by brand
* Average price by model year
* Fuel type distribution
* Automatic vs Manual transmission analysis
* Interactive slicers for:

  * City
  * Brand
  * Fuel Type
  * Transmission
  * Model Year

---

## 🛠️ Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* Star Schema Data Model
* CSV Dataset
* Data Cleaning & Transformation

---

## 🗂️ Dataset

The dataset contains vehicle advertisements from Avito, including:

| Column            | Description        |
| ----------------- | ------------------ |
| Marque            | Vehicle Brand      |
| Ville             | City               |
| Prix              | Vehicle Price      |
| Année-Modèle      | Manufacturing Year |
| Carburant         | Fuel Type          |
| Boite de vitesses | Transmission Type  |
| Kilométrage       | Mileage            |
| Age               | Vehicle Age        |

---

## ⭐ Data Preparation

The following steps were performed before creating the dashboard:

* Removed duplicate records
* Handled missing values
* Converted data types
* Standardized text values
* Created calculated columns
* Built a Star Schema
* Created dimension tables:

  * Dim_Brand
  * Dim_City
  * Dim_Fuel
  * Dim_Transmission
  * Dim_Year

---

## 📈 Key Insights

* Renault, Volkswagen, and Dacia have the highest number of listings.
* Vehicle prices generally increase for newer model years.
* Hybrid and electric vehicles tend to have higher average prices.
* Manual transmission vehicles remain the most common in the dataset.
* The dashboard enables users to compare prices across cities, brands, and fuel types.

---

## 📷 Dashboard Preview

### Main Dashboard

* Interactive KPI cards
* Brand analysis
* Price analysis
* Fuel distribution
* Model year trends

---

## 🚀 How to Use

1. Open the `avito.pbix` file using **Power BI Desktop**.
2. Refresh the dataset if necessary.
3. Use the slicers to filter the dashboard by:

   * City
   * Brand
   * Fuel Type
   * Transmission
   * Model Year
4. Interact with the charts to explore market insights.

---

## 📂 Project Structure

```text
📁 Avito-Vehicle-Market-Analysis
│
├── avito.pbix
├── README.md
├── images/
│   ├── dashboard1.png
│   └── dashboard2.png
└── dataset/
    └── AVITO.csv
```

---

## 📚 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling (Star Schema)
* DAX Measures
* Power Query
* Data Visualization
* Dashboard Design
* Business Intelligence
* Data Analysis

---

## 👩‍💻 Author

**Meryem Laalioui**

* Aspiring Data Analyst
* Full-Stack Developer
* Passionate about Business Intelligence, Data Visualization, and Machine Learning

---

## 📄 License

This project is intended for educational and portfolio purposes.

---

# ⭐ If you find this project useful, feel free to star the repository and share your feedback!
