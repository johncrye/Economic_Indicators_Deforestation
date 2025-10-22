# Economic_Indicators_Deforestation

# 🌎 Environmental Change & Energy Systems Analysis

**Analyzing Deforestation in the Amazon and Electricity Generation in South America**

## 📘 Project Overview

This project combines two complementary datasets and analyses:

1. **Amazon Forest Cover Loss** – a geospatial and statistical analysis of deforestation patterns across the Amazon basin.
2. **Electricity Generation in South America (SAM)** – a data-driven assessment of energy generation trends, capacity mixes, and emissions in the region.

Together, these notebooks explore the intersection between **land-use change** and **energy transition**, highlighting how resource management and renewable energy development influence regional sustainability outcomes.

---

## 📂 Repository Structure

```
├── Amazon Forest Cover Loss.ipynb        # Deforestation analysis and visualization
├── electricity_generation_SAM.ipynb      # Electricity generation analysis for South America
├── data/                                 # (Expected) input datasets – e.g., CSV, shapefiles
├── outputs/                              # Exported charts, maps, and summaries
├── README.md                             # Project documentation
└── requirements.txt                      # (Optional) Python dependencies
```

---

## ⚙️ Setup & Dependencies

To run the notebooks locally, install the required dependencies.
You can create a virtual environment and install packages with:

```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

If `requirements.txt` isn’t available, install key libraries manually:

```bash
pip install pandas numpy matplotlib seaborn geopandas folium plotly
```

For geospatial analysis, ensure **GDAL** and **Fiona** are installed properly (these often require system-level dependencies).

---

## 🧭 Notebook Summaries

### 1. Amazon Forest Cover Loss.ipynb

**Purpose:**
Analyze satellite-based forest cover change to quantify and visualize deforestation trends in the Amazon basin.

**Key Components:**

* Data loading and preprocessing of forest cover and loss datasets
* Temporal trend analysis of deforestation rates
* Regional comparison across Brazil, Peru, Colombia, etc.
* Map-based visualization using `GeoPandas` and `Folium`
* Identification of high-risk zones for conservation prioritization

**Outputs:**

* Forest loss time series by region
* Interactive deforestation heatmaps
* Summary tables for annual change rates

---

### 2. electricity_generation_SAM.ipynb

**Purpose:**
Explore electricity generation data across South American countries, focusing on renewable vs. non-renewable capacity and emissions profiles.

**Key Components:**

* Data ingestion of energy statistics from regional datasets (IEA, EMBER, or local sources)
* Aggregation of generation by fuel type (hydro, solar, wind, fossil fuels)
* Visualization of national energy mixes and capacity trends
* Correlation analysis between deforestation and energy infrastructure growth (optional cross-link)

**Outputs:**

* Electricity generation trend plots
* Energy mix comparison charts
* Carbon intensity and renewable penetration insights

---

## 📊 Integration Insights

By linking deforestation and energy system dynamics, the project supports broader sustainability questions:

* How does hydroelectric expansion correlate with forest loss?
* Which regions show simultaneous gains in renewables and losses in forest cover?
* What policy or investment opportunities could reduce environmental trade-offs?

---

## 🧩 Next Steps

* Integrate datasets to build a combined **“Energy–Forest Trade-off Index.”**
* Extend the electricity model to include projected renewable growth scenarios.
* Publish results via interactive dashboard (e.g., Plotly Dash or Streamlit).

---

## 🧠 Author & License

**Author:** John Crye
**License:** MIT License (or specify another if preferred)
