# COVID-19 Analysis and Visualization using Plotly Express

This project analyzes and visualizes COVID-19 data using `Plotly Express`, `Pandas`, and other Python libraries. It demonstrates various types of visualizations to better understand the trends, patterns, and distribution of COVID-19 cases worldwide.

---

## Project Overview

The project involves:
- Importing and exploring COVID-19 datasets.
- Cleaning and manipulating the data.
- Generating interactive visualizations to represent the pandemic's impact.

---

## Datasets Used

1. **Dataset 1**: `covid.csv`
   - Contains country-wise COVID-19 statistics, including cases, deaths, recoveries, and tests.
   - **Shape**: `(209, 17)`

2. **Dataset 2**: `covid_grouped.csv`
   - Contains daily grouped data for COVID-19 metrics by country.
   - **Shape**: `(35156, 11)`

3. **Dataset 3**: `coviddeath.csv`
   - Contains data related to COVID-19 deaths.
   - Used for additional analysis.

---

## Libraries and Tools

The following Python libraries are used in this project:
- **Pandas**: For data manipulation and analysis.
- **Plotly Express**: For creating interactive visualizations.
- **Matplotlib**: For additional plotting options.
- **Plotly Graph Objects**: For advanced visualizations.

---

## Visualizations Included

1. **Bar Charts**:
   - Total cases, deaths, and tests by country and continent.
   - Horizontal and vertical orientations.

2. **Scatter Plots**:
   - Comparing total cases, deaths, and tests by country and continent.
   - Logarithmic scales for better representation of data distribution.

3. **Line Plots**:
   - Daily trends for confirmed, recovered, and death cases.

4. **Choropleth Maps**:
   - Animated maps showing COVID-19 metrics (confirmed cases, deaths, recoveries) over time.

5. **Other Visualizations**:
   - Comparison of regions based on WHO classification.
   - New cases trends over time.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/COVID19-Analysis.git
