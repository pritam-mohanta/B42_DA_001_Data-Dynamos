# Solar Power Plant Analysis Dashboard

## Overview
This project is a Streamlit-based dashboard designed to analyze and visualize data from a solar power plant. The dashboard provides insights into power generation, weather conditions, and efficiency metrics. It is built to help users explore trends, identify patterns, and make data-driven decisions.

## Key Features
- **Interactive Date Selection**: Users can select a date range to filter and analyze data.
- **Key Performance Indicators (KPIs)**: Displays critical metrics such as total DC/AC power, ambient/module temperature, and irradiation.
- **Visualizations**:
  - Power distribution (AC and DC) using pie charts.
  - Correlation heatmap for weather and generation data.
  - Time-series trends for DC/AC power and daily yield.
  - Efficiency and power loss analysis.
  - Impact of temperature on power generation.
- **Customizable KPIs**: Users can select specific KPIs to display based on their interests.
- **Enhanced UI**: Styled with custom CSS for a professional and visually appealing interface.

## How to Run the Application Locally

### Prerequisites:
- Python 3.8 or higher.
- Required Python libraries: `streamlit`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`.

### Installation:

#### 1. Clone the repository:
```bash
git clone <repository-url>
```
#### 2. Navigate to the project directory:
```bash
cd <project-directory>
```
#### 3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
#### 4. Run the Application:
```bash
streamlit run app.py
```
The app will open in your default web browser 

## Data Files:
Ensure the following CSV files are in the project directory:
- `Plant_1_Generation_Data.csv`
- `Plant_1_Weather_Sensor_Data.csv`

## Screenshots of the Dashboard

### **1. Main Dashboard**
- Displays KPIs, power distribution charts, and date selection options.

### **2. Correlation Heatmap**
- Visualizes correlations between weather and generation data.

### **3. Power Trends**
- Time-series plots for DC/AC power and daily yield.

### **4. Efficiency Analysis**
- Line chart showing daily efficiency trends.

### **5. Temperature Impact**
- Scatter plots showing the relationship between temperature and power output.

## Deployment Information
The application is deployed on **Streamlit Cloud** and can be accessed via the following link:

🔗 **https://soloar-power-plant-analysis.streamlit.app/**

## Additional Notes
- **Data Preprocessing**:
  - The data is cleaned and merged before analysis.
  - Missing or invalid values are handled appropriately.
- **Customization**:
  - Users can modify the code to include additional KPIs or visualizations.
- **Performance Optimization**:
  - The app uses Streamlit’s caching mechanism (`@st.cache_data`) to improve performance.

## Future Enhancements
- Add support for multiple plants or datasets.
- Include **machine learning models** for predictive analysis.
- Enable **data export functionality** for further analysis.

---
This documentation provides a **comprehensive guide** to understanding, running, and customizing the **Solar Power Plant Analysis Dashboard**.  
For any **questions or feedback**, feel free to reach out! 🌞
Contact
📧 **Email**: [abhishekfbd02@gmail.com]


