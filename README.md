# Accident-Analysis-using-Python
Accident Analysis using Python
# 🚗 Accident Analysis Using Python

## 📌 Project Overview

**Accident Analysis** is a **Python Data Analysis and Exploratory Data Analysis (EDA)** project focused on understanding road accident patterns.

The project analyzes accident-related information such as **driver characteristics, vehicle details, road conditions, weather conditions, casualty information, causes of accidents, and accident severity**.

Python is used to clean, explore, analyze, and visualize the dataset to identify meaningful patterns in road accidents.

---

## 🎯 Problem Statement

Road accident data contains information about drivers, vehicles, road conditions, weather, casualties, accident causes, and severity. Analyzing this information manually can make it difficult to identify important accident patterns and understand the factors associated with accident severity.

Therefore, this project uses **Python-based data analysis and visualization** to explore the accident dataset and identify meaningful patterns related to road accidents.

---

## 🎯 Project Objectives

* To understand and explore the accident dataset using Python.
* To inspect the dataset structure, columns, data types, and statistical information.
* To identify and analyze missing values.
* To perform data cleaning and preprocessing.
* To analyze accident patterns based on **day of the week**.
* To analyze driver characteristics such as **age group, gender, education, and driving experience**.
* To analyze different **types of vehicles** involved in accidents.
* To examine road-related factors such as road surface, road conditions, lanes, and junction types.
* To analyze **weather and light conditions** associated with accidents.
* To identify major **causes of accidents**.
* To analyze **accident severity** and casualty-related information.
* To create meaningful visualizations using Python.
* To generate insights from the accident data through EDA.

---

## 📂 Dataset Description

The dataset contains **12,316 accident records and 32 columns**.

### Major Dataset Features

| Category   | Features                                                                    |
| ---------- | --------------------------------------------------------------------------- |
| Time       | Time, Day of Week                                                           |
| Driver     | Age Band, Sex, Education, Driving Experience                                |
| Vehicle    | Vehicle Type, Vehicle Ownership, Vehicle Service Year                       |
| Road       | Area, Lanes/Median, Road Alignment, Junction Type                           |
| Conditions | Road Surface, Road Surface Conditions, Light Conditions, Weather Conditions |
| Accident   | Type of Collision, Vehicle Movement, Cause of Accident                      |
| Casualty   | Number of Casualties, Casualty Class, Casualty Sex, Casualty Age            |
| Severity   | Casualty Severity, Accident Severity                                        |

The dataset contains both **categorical and numerical variables**.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Inspection
   ↓
Missing Value Analysis
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Pattern Analysis
   ↓
Business Insights
   ↓
Conclusion
```

---

## 🔍 Data Exploration

The dataset was explored using Python functions such as:

* `head()`
* `columns`
* `info()`
* `describe()`
* `isnull().sum()`
* `unique()`

The dataset contains **30 object-type columns and 2 integer columns**.

The numerical variables include:

* `Number_of_vehicles_involved`
* `Number_of_casualties`

The average number of vehicles involved per accident is approximately **2.04**, while the average number of casualties is approximately **1.55**.

---

## 🧹 Data Cleaning

Missing-value analysis was performed to identify incomplete data.

Missing values were observed in several fields, including:

* Educational Level
* Vehicle Driver Relation
* Driving Experience
* Type of Vehicle
* Owner of Vehicle
* Service Year of Vehicle
* Defect of Vehicle
* Area Accident Occurred
* Lanes or Medians
* Types of Junction
* Type of Collision
* Vehicle Movement
* Work of Casuality
* Fitness of Casuality

The notebook contains a dedicated **Data Cleaning** stage to prepare the dataset for further analysis.

---

## 📊 Exploratory Data Analysis

The project explores different dimensions of accident data, including:

### 👨‍✈️ Driver Analysis

Driver-related factors such as:

* Age group
* Gender
* Education
* Driving experience

are analyzed to understand accident patterns.

### 🚗 Vehicle Analysis

Different vehicle types involved in accidents are examined, including automobiles, public vehicles, lorries, motorcycles, Bajaj, taxis, and other vehicle categories.

### 🛣️ Road & Environmental Analysis

The project considers:

* Road alignment
* Junction type
* Road surface type
* Road surface conditions
* Light conditions
* Weather conditions

to understand accident patterns under different road and environmental conditions.

### ⚠️ Accident Cause Analysis

The `Cause_of_accident` column is analyzed to identify common accident causes such as:

* Moving Backward
* Overtaking
* Changing Lane
* No Distancing
* Other recorded causes

### 🩹 Accident Severity Analysis

The `Accident_severity` variable is used to understand the severity of reported accidents, including categories such as:

* Slight Injury
* Serious Injury

The dataset also contains casualty-related severity information.

---

## 💡 Key Analysis Areas

The project focuses on answering questions such as:

1. Which days have more recorded accidents?
2. Which driver age groups are commonly involved?
3. How does driver gender vary across accidents?
4. Which vehicle types are frequently involved?
5. What are the common causes of accidents?
6. How do weather conditions relate to accident occurrence?
7. How do light conditions vary across accidents?
8. What road conditions are associated with accidents?
9. What is the distribution of accident severity?
10. How do the number of vehicles and casualties vary across accidents?

---

## 📈 Visualizations

Python visualization libraries are used to represent accident patterns through:

* Bar charts
* Count plots
* Histograms
* Box plots
* Heatmaps
* Other EDA visualizations

These visualizations make categorical distributions, numerical patterns, and relationships easier to understand.

---

## 💼 Business Interpretation

The analysis can help understand accident patterns across **drivers, vehicles, roads, environmental conditions, accident causes, and severity**.

Such analysis can support data-driven understanding of accident-prone patterns and provide useful information for further road-safety analysis.

**Note:** This project is an exploratory data analysis project and does not establish causal relationships between the analyzed variables.

---

## 🏁 Conclusion

The **Accident Analysis Using Python** project demonstrates the complete workflow of a Python-based Data Analysis project.

It covers **data loading, data inspection, missing-value analysis, data cleaning, exploratory analysis, visualization, and interpretation**.

The project demonstrates practical skills in **Pandas, NumPy, Matplotlib, Seaborn, data cleaning, EDA, and data visualization**, making it suitable as a **Python Data Analysis project**.

---

## 👩‍💻 Author

**Reena Shri**

**Project:** Accident Analysis Using Python
**Project Type:** Python Data Analysis / EDA
