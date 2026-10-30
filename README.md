# Climate Factors and Agricultural Yields
### Exploring the Relationship Between Climate Conditions and Crop Productivity Across Indian States

## 1. Introduction

Agriculture is closely influenced by environmental conditions such as rainfall, temperature, humidity and soil composition. Understanding how these factors relate to crop productivity can help identify agricultural patterns and support better-informed planning.

**Climate Factors and Agricultural Yields** is a Business Analytics project that explores the relationship between climatic conditions and agricultural performance across different Indian states.

Using Excel for data handling and Power BI for analysis and visualization, the project examines crop production, cultivated area and yield across different years, seasons and geographical regions. It also explores how temperature, precipitation and humidity vary across crops and how these variations relate to agricultural yield.

The objective is to transform agricultural data into meaningful insights through interactive dashboards rather than make unsupported assumptions about the causes of changes in crop productivity.

## 2. Project Objectives

- Analyze agricultural production and yield across Indian states.
- Examine the relationship between temperature, rainfall and humidity and crop yield.
- Compare agricultural performance across Kharif, Rabi and Annual seasons.
- Identify crops and geographical regions with comparatively higher production.
- Build an interactive dashboard to support data exploration and business-style decision-making.

## 3. Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Dataset inspection, data organization and preliminary analysis |
| Power BI | Data modeling, visualizations and interactive dashboard development |
| Power Query | Data transformation and preparation |
| DAX | Calculated measures and KPI development |

**Domain:** Business Analytics / Agriculture

## 4. Dataset Overview

The project uses a dataset containing 5,000 agricultural records covering the period 1997–2014.

The dataset includes the following attributes:

| Category | Variables |
|---|---|
| Geography | State Name, District |
| Time | Crop Year, Season |
| Agriculture | Crop, Area, Production, Yield |
| Climate | Temperature, Precipitation, Humidity |
| Soil | Soil Type |

**Analytical dimensions:**
- 10 Indian states
- 8 crop categories
- 3 seasonal categories
- 7 soil types
- 18 years of observations

*Note: The supplied dataset is synthetic. Its results are intended for analytical practice and dashboard demonstration, not as verified official agricultural statistics.*

## 5. Dashboard and Visualizations

The Power BI dashboard provides an interactive overview of agricultural production and climate-related patterns.

![Climate Factors and Agricultural Yields Dashboard](images/dashboard.png)

### Key Dashboard Components

**A. KPI Cards**

Provides a quick overview of:
- Total Production
- Total Cultivated Area
- Average Temperature
- Average Rainfall
- Weighted Average Yield

**B. Production by Crop**

A comparative visualization showing how total agricultural production is distributed across different crops, helping identify the major contributors to overall output.

**C. Crop by Season**

A donut chart displaying the distribution of records across Kharif, Rabi and Annual categories.

**D. Climate and Yield Analysis**

Three scatterplots explore the relationship between:
- Yield vs Humidity
- Yield vs Precipitation
- Yield vs Temperature

These visualizations help identify patterns, clusters and possible associations between climatic variables and crop productivity.

**E. Interactive Filters**

Users can explore the dashboard using:
- Year range
- Crop
- State
- Season
- Soil Type

### Key Observations

Based on the current dashboard:

1. **Sugarcane dominates production:** It contributes approximately 73% of total production (215M out of 294M tonnes).
2. **Climate relationships vary by crop:** The scatterplots suggest different yield patterns across crops when compared against rainfall, temperature and humidity.
3. **Rice shows a comparatively positive relationship:** Its yield displays a slight positive association with the three climate variables in the current analysis.
4. **Sugarcane shows weaker climate sensitivity:** Its yield patterns appear comparatively stable across the observed climate ranges.
5. **Yield excluding sugarcane is more stable:** Removing sugarcane helps make comparisons between the other crops easier to interpret.

These are exploratory observations from the supplied dataset, not evidence of causation.

## 6. How to Use the Dashboard

1. Open the Power BI dashboard file (`.pbix`) using Microsoft Power BI Desktop.
2. Use the Year slider to select a particular time period.
3. Select a crop to examine its production and yield patterns.
4. Choose a state to compare geographical differences.
5. Use the Season buttons to explore Kharif, Rabi and Annual records.
6. Select a soil type to investigate patterns across different soil categories.
7. Observe how the KPI cards and visualizations change with the selected filters.
8. Hover over charts to view additional information through tooltips.

**Tip:** Start with the overall dashboard view before applying filters. This makes it easier to understand the broader distribution of agricultural production.

## 7. Getting Started

### Prerequisites

- Microsoft Excel
- Microsoft Power BI Desktop
- Basic understanding of data analysis and visualization

### Installation and Setup

1. Clone or download this repository.
2. Open the Excel dataset from the `Dataset` folder.
3. Open the `.pbix` file from the `Dashboard` folder using Power BI Desktop.
4. If required, update the dataset source path in Power BI.
5. Refresh the data to load the dataset.
6. Explore the dashboard using the available filters and visualizations.

## 8. Contributor Instructions

Contributions and suggestions are welcome.

To contribute:

1. Fork this repository.
2. Create a new branch for your changes.
3. Make the required modifications to the dataset, dashboard or documentation.
4. Test the updated dashboard in Power BI Desktop.
5. Commit your changes with a descriptive commit message.
6. Submit a Pull Request explaining the changes.

## 9. Contribution Guidelines

- Maintain consistency in column names, data types and units.
- Ensure that data transformations do not introduce unintended errors.
- Use appropriate visualizations for the analytical question being addressed.
- Clearly label charts, axes, KPIs and measurement units.
- Avoid presenting correlation as causation.
- Document new calculated measures and significant changes.
- Keep the dashboard clean, readable and easy to navigate.

## 10. Known Issues and Limitations

- The dataset is synthetic and does not represent verified real-world agricultural statistics.
- The analysis covers a limited set of states, crops and years.
- Correlations do not establish causal relationships between climatic conditions and crop yield.
- Agricultural productivity is influenced by additional factors such as irrigation, farming practices, fertilizers, technology and pest conditions, which are not fully represented.
- Comparisons of total production should account for differences in cultivated area and crop characteristics.
- Sugarcane has a substantially higher yield scale than other crops, which can make direct comparisons difficult.
- Dashboard results depend on the selected filters and the underlying dataset.

## 11. Future Scope

Potential improvements include:

- Integrating verified agricultural and meteorological datasets.
- Expanding geographical coverage to include more Indian states and districts.
- Introducing year-over-year comparisons and trend analysis.
- Examining the influence of soil characteristics and seasonal variations in greater detail.
- Adding regional comparisons and more advanced statistical analysis.
- Developing predictive models as a separate extension of the project.

## 12. Acknowledgements

This project was developed as part of an exploration of Business Analytics, agricultural data and interactive visualization using Microsoft Excel and Power BI.

**Project:** Climate Factors and Agricultural Yields  
**Domain:** Business Analytics / Agriculture  
**Tools:** Microsoft Excel | Power BI | Power Query | DAX
