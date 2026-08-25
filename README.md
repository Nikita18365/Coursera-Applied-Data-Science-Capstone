# Coursera-Applied-Data-Science-Capstone
10 course, Final task - Applied Data Science Capstone

# SpaceX Falcon 9 Landing Prediction — Applied Data Science Capstone

This repository contains my final project for the **Applied Data Science Capstone** course on Coursera.

The project brings together the main data science techniques covered throughout the course: data collection, data wrangling, exploratory data analysis, SQL, interactive visualization, dashboard development, and machine learning.

The main goal of the project is to analyze **SpaceX Falcon 9 launch data** and build machine learning models to predict whether the first stage of the rocket will successfully land.

## Project Workflow

The repository is organized according to the main stages of the project:

```text
📁 1. Сбор данных
📁 2. Обработка данных
📁 3. Исследовательский анализ с использованием sql
📁 4. Исследовательский анализ с использованием Pandas и Matplotlib
📁 5. Визуальная аналитика с Folium
📁 6. Интерактивная приборная панель с помощью Plotly Dash
📁 7. Предиктивный анализ
📄 Отчет по итоговому проекту по науке о данных.pdf
```

### 1. Data Collection

Collection of SpaceX launch data from available data sources and preparation of the initial dataset for further analysis.

### 2. Data Wrangling

Cleaning and transforming the collected data, processing missing values, selecting relevant features, and preparing the dataset for exploratory analysis and machine learning.

### 3. Exploratory Data Analysis with SQL

Analysis of launch data using SQL queries to investigate launch sites, payloads, mission outcomes, booster versions, and other important characteristics.

### 4. Exploratory Data Analysis with Pandas and Matplotlib

Exploratory analysis using Python, Pandas, and visualization libraries to identify relationships between launch characteristics and successful first-stage landings.

### 5. Interactive Visual Analytics with Folium

Geospatial analysis of SpaceX launch sites using interactive maps.

The analysis includes:

* launch site locations;
* successful and unsuccessful launches;
* proximity of launch sites to coastlines;
* proximity to highways;
* proximity to railways;
* distance from nearby cities.

### 6. Interactive Dashboard with Plotly Dash

Development of an interactive dashboard that allows users to:

* select individual launch sites;
* compare successful and failed launches;
* analyze payload ranges;
* investigate the relationship between payload mass and mission outcome;
* compare different Falcon 9 booster versions.

### 7. Predictive Analysis

Development and evaluation of machine learning models for predicting Falcon 9 first-stage landing success.

The project includes several classification approaches, such as:

* Logistic Regression;
* Support Vector Machine;
* Decision Tree;
* K-Nearest Neighbors.

The models are tuned and compared using classification accuracy and test-set performance.

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **SQL**
* **Matplotlib**
* **Seaborn**
* **Folium**
* **Plotly**
* **Dash**
* **Scikit-learn**
* **Jupyter Notebook**

## Main Questions

The project investigates several questions related to Falcon 9 launches:

* Which launch sites demonstrate the highest number of successful launches?
* How does launch success vary between different launch sites?
* Is payload mass related to first-stage landing success?
* Which payload ranges demonstrate higher success rates?
* How do different Falcon 9 booster versions perform?
* Are there geographical patterns in the locations of SpaceX launch sites?
* Can machine learning models predict whether the first stage will land successfully?

## Final Report

The repository also contains the final project presentation:

**`Отчет по итоговому проекту по науке о данных.pdf`**

It summarizes the complete project workflow, including data collection, exploratory analysis, visualizations, dashboard results, machine learning models, and final conclusions.

## Course

**Applied Data Science Capstone**
Coursera

This project was completed as the capstone project of my data science coursework and demonstrates an end-to-end data science workflow from raw data collection to interactive analytics and predictive modeling.
* an example of an end-to-end applied data science project;
* a portfolio project demonstrating practical skills in Python, SQL, data visualization, dashboard development, geospatial analysis, and machine learning.
