# 🏅 Olympic Analysis System

**Olympic Analysis System** is an interactive data visualization and analytics tool built using **Streamlit**, **Pandas**, and **Plotly**. It offers insightful visualizations and statistics about the Olympic Games, including medal tallies, country-wise performances, and athlete-specific analysis.

---

## 📌 Features

### 🎖️ Medal Tally
- View overall medal standings by year and country.
- Dynamic selection of year and country with real-time table updates.

### 🌍 Overall Analysis
- Key statistics: Total editions, host cities, sports, events, athletes, and nations.
- Year-wise trends of participation, events, and athlete counts.
- Heatmap of sports over time and list of most successful athletes.

### 🇨🇳 Country-wise Analysis
- Country-specific performance trends across years.
- Sport-wise strength heatmap.
- Top athletes from selected countries.

### 🧍 Athlete-wise Analysis
- Age distribution of medal winners (Gold, Silver, Bronze).
- Age distribution across major sports.
- Height vs Weight scatter plots.
- Participation trends for men vs women over the years.

---

## 🛠️ Technologies Used

- **Python 3**
- **Streamlit** – for building the web app interface
- **Pandas** – for data manipulation
- **Plotly & Seaborn** – for rich visualizations
- **Matplotlib** – for heatmaps and custom plots

---

## 📁 Project Structure

###OAS
- app.py # Main Streamlit app
- helper.py # Core logic functions
- preprocessor.py # Data cleaning and preprocessing
- athlete_events.csv # Main dataset
- noc_regions.csv # Country region mapping
- README.md # Project documentation
