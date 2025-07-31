# 🗺️ Interactive Population Projection & Infrastructure Analysis in Kazakhstan

This project combines **data analysis**, **machine learning**, and **engineering modeling principles** to build an **interactive and predictive visualization tool** that forecasts **city-level population** and **infrastructure needs** across Kazakhstan. The result is a system that supports urban planning and decision-making by projecting future demand based on past and current statistical trends.

---

## 📌 Project Overview

- Cleaned and analyzed demographic and infrastructure data for major Kazakhstani cities.
- Built predictive models to forecast:
  - Population growth (2025–2029)
  - Per capita availability of hospitals and doctors
- Generated high-quality **visualizations** for decision support.
- Applied **linear regression with noise simulation** to reflect more realistic growth patterns.
- Removed anomalous administrative regions for accurate projections.
- Final data is intended for integration into an **interactive map or dashboard**.

---

## 🔑 Key Features

- 📊 **Complex Multisource Data Processing**: Integrated datasets for population, birth rates, death rates, migration, hospitals, and doctors across multiple years.
- 🧼 **Advanced Data Cleaning**: Converted localized formats, handled placeholder values, normalized demographic ratios per 100,000 residents.
- 🤖 **Predictive Modeling**:
  - Used **average growth rate models** for population.
  - Applied **linear regression** with noise factors for infrastructure forecasts.
- 🌐 **City-by-City Forecasting**: Each city has its own independent model reflecting local trends.
- 📈 **Impactful Visualizations**:
  - Forecast curves by city from 2019 to 2029.
  - Separate trends for the nation and individual cities.
- 💡 **Engineering-Driven Forecasting**: Incorporates statistical modeling and engineering judgment to improve estimation accuracy.

---

## 📁 Datasets Used

| Dataset     | Description                               |
|-------------|-------------------------------------------|
| `population.xlsx` | Historical population (city-level)     |
| `birth.xlsx`      | Annual birth statistics                |
| `death.xlsx`      | Annual death statistics                |
| `migration.xlsx`  | Internal and external migration data   |
| `hospitals.xlsx`  | Number of hospitals per city (if used) |
| `doctors.xlsx`    | Number of doctors per city (if used)   |

---

## 🛠 Technologies & Tools

- Python 3
- Pandas & NumPy
- Scikit-learn (LinearRegression)
- Matplotlib
- Plotly Express
- Jupyter / Google Colab

---

## 🧪 How It Works

1. **Data Ingestion**: Load and clean raw `.xlsx` files.
2. **Preprocessing**:
   - Remove incomplete regions.
   - Normalize all metrics and structure by year.
3. **Modeling**:
   - Use growth rates to project population.
   - Use linear regression for hospitals/doctors per capita.
4. **Visualization**:
   - Plot multiyear trends for each city.
   - Export merged datasets for mapping tools.

---

## 📍 Future Improvements

- Integration with web-based **interactive dashboards** (e.g., Streamlit or Dash)
- Use of **geospatial data (GeoJSON)** for choropleth maps
- Incorporation of **economic indicators** or **education levels**
- Improved forecasting using LSTM or Prophet models

---

## 📦 Output

- `all_population.csv`: Final city-level projections for 2025–2029
- Projection plots for national and city-specific trends
- Ready-to-map datasets for interactive visualization

---

## Interactive Map Link on Figma

https://www.figma.com/proto/P7hBiBzc3oWUwNsyso9Vrf/raha-temp?page-id=0%3A1&node-id=1-10&p=f&viewport=417%2C599%2C0.02&t=JdCd5rUwcmt5eB7u-1&scaling=scale-down-width&content-scaling=fixed&starting-point-node-id=1%3A10
