# Exploratory Data Analysis (EDA) for Weather and Solar Dataset

**Exploratory Data Analysis (EDA) for Weather and Solar Dataset** project! This repository contains in-depth data cleaning, analysis, and visualization processes to uncover insights from environmental and solar-related datasets.

---

## **Project Overview**

The project focuses on analyzing weather and solar energy data to:

- **Identify trends** in key variables like solar irradiance, temperature, and wind speed.
- **Handle anomalies** and missing data to ensure data quality.
- Provide actionable insights for energy and climate-related decision-making.

---

## **Key Features**

- **Comprehensive EDA**: Analyze metrics like `GHI`, `DNI`, `DHI`, temperatures (`ModA`, `ModB`), and wind conditions (`WS`, `WSgust`).
- **Data Cleaning**:
  - Removed invalid values (e.g., negative irradiance values).
  - Filled missing values with meaningful estimates (e.g., column means).
  - Dropped redundant columns like `Comments`.
- **Statistical Summaries**:
  - Generated descriptive statistics for all variables.
  - Identified outliers and inconsistencies in the dataset.
- **Visualizations**:
  - Temporal trends in solar irradiance and weather conditions.
  - Correlation heatmaps for key variables.

---

## **Dataset Information**

The dataset includes the following variables:

- **Timestamp**: The date and time of each observation.
- **GHI, DNI, DHI**: Solar irradiance metrics (Global, Direct, and Diffuse Horizontal Irradiance).
- **ModA, ModB**: Module temperatures.
- **Tamb**: Ambient temperature.
- **RH**: Relative humidity.
- **WS, WSgust**: Wind speed and gusts.
- **BP**: Barometric pressure.
- **Precipitation**: Measured precipitation levels.

---

## **Setup Instructions**

To run the analysis locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Nahom-ketsela/kaim-week-00.git
   ```
2. Install required dependencies:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the analysis in the notebook file.

---

## **Key Insights**

- **Solar Irradiance**: Exhibits strong seasonal trends with occasional negative values requiring correction.
- **Temperature**: Ambient temperatures are consistent with tropical climates (mean ~28°C).
- **Wind Data**: Wind speeds and gusts show variability, with occasional extreme conditions.
- **Precipitation**: Minimal, reflecting dry weather conditions during the recording period.
