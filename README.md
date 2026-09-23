# ♻️ Jakarta Waste Volume Analysis

A data analysis project exploring waste volume patterns across administrative regions and sub-districts in Jakarta. This project was developed as an SDG-related case study to understand how waste generation varies across different areas and activity patterns.

## 🎯 Project Overview

The analysis focuses on waste volume distribution in Jakarta using several visualizations to examine:

* Waste volume by administrative region
* Average daily waste volume
* Sub-districts with the highest waste volume
* Daily waste volume trends
* Relationship between area size and waste volume

The findings are presented through data visualizations and an infographic to make the analysis easier to understand.

## 📊 Analysis

### 1. Waste Volume by Region

Compares the percentage of total waste volume and average daily waste volume across Jakarta's administrative regions.

West Jakarta records the highest waste volume, followed by Central Jakarta and South Jakarta.

### 2. Top 5 Sub-Districts

Identifies the sub-districts with the highest total waste volume during the analyzed period.

The analysis highlights areas with high population density and intensive residential, commercial, educational, and administrative activities.

### 3. Daily Waste Trend

Examines changes in waste volume throughout the analyzed month and identifies several dates with noticeable increases in waste volume.

### 4. Area Size vs. Waste Volume

A scatter plot is used to examine the relationship between administrative area size and average daily waste volume.

The analysis obtained a Pearson correlation of **-0.0876**, indicating a very weak linear relationship between area size and waste volume.

This suggests that waste generation is not determined by physical area alone and may also be related to population density, land use, and the intensity of daily activities.

## 💡 Key Findings

* West Jakarta has the highest total and average daily waste volume among the analyzed regions.
* Several high-waste sub-districts are concentrated in areas with intensive residential and commercial activities.
* Waste volume varies across different days, with several noticeable peaks during the analyzed period.
* Administrative area size has little linear relationship with waste volume, with a Pearson correlation of **-0.0876**.
* Waste management planning should consider activity intensity and area characteristics rather than relying only on physical area size.

## 🌱 SDG Relevance

This project is related to the **Sustainable Development Goals (SDGs)**, particularly **SDG 11: Sustainable Cities and Communities**, through its focus on urban waste management and sustainable city development.

The analysis can support discussions on more targeted waste collection, transportation efficiency, waste sorting, and public awareness.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📁 Repository Structure

```text
jakarta-waste-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── jakarta_waste_analysis.ipynb
│
├── infographic/
│   ├── jakarta_waste_infographic.png
│   └── jakarta_waste_infographic.pdf
│
├── report/
│   └── infographic_description.pdf
│
└── README.md
```

## 📚 Data Sources

* Jakarta Government — Jakarta Administrative Area and Population Information
  https://www.jakarta.go.id/tentang-jakarta

* Waste volume dataset used for the analysis is provided in the `data/` directory.

## 👥 Project Type

**SDG Case Study & Data Analysis Project**

Focus: Urban Waste Management in Jakarta
SDG: **SDG 11 — Sustainable Cities and Communities**
