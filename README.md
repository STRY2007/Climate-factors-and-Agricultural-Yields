# Climate-factors-and-Agricultural-Yields


## About the Project

Agriculture depends on several factors, including rainfall, temperature, humidity, soil conditions, and growing seasons. However, these factors can vary from one region to another, and crop yields can vary too.

This project explores how these climate and agricultural factors relate to crop productivity across different Indian states and districts. Using Excel and Power BI, I aim to analyze the data, identify useful patterns, and present the findings through an interactive dashboard.

The idea is to make agricultural data easier to understand and see how data analysis can help support better agricultural planning and decision-making.

**Note:** The dataset currently used for this project is synthetic and created for learning purposes. It does not represent verified agricultural records from India.

## What I Want to Find Out

Through this project, I want to answer a few questions:

- Which states and districts have higher average crop yields?
- Which crops contribute the most to total agricultural production?
- Does crop yield vary across Kharif, Rabi, and other growing seasons?
- How are rainfall, temperature, and humidity related to crop yields?
- How have crop production and yield changed over the years?
- Do different soil types show any noticeable differences in productivity?

## Tools Used

- **Microsoft Excel:** To clean the data, check for inconsistencies, and perform basic analysis.
- **Power Query:** To organize and transform the dataset.
- **Power BI:** To build an interactive dashboard and present the findings visually.

## Dataset

The dataset contains 5,000 synthetic records covering different Indian states, districts, crops, years, and growing seasons.

It includes the following information:

| Column | What it represents |
|---|---|
| State_Name | Name of the state |
| District | Name of the district |
| Crop_Year | Year of the record |
| Season | Agricultural season |
| Crop | Type of crop |
| Area (ha) | Land area used for cultivation |
| Production (tonnes) | Total crop production |
| Yield (kg/ha) | Crop productivity per hectare |
| Temperature (°C) | Temperature associated with the record |
| Precipitation (mm) | Rainfall or precipitation |
| Humidity (%) | Relative humidity |
| Soil_Type | Type of soil |

Since the dataset is synthetic, any patterns found during the analysis are useful for practicing data analysis but should not be treated as actual agricultural findings.

## Dashboard Overview

The Power BI dashboard is designed to bring the main findings together in one place.

It aims to include:

- **Key Performance Indicators:** Total production, cultivated area, average yield, average temperature, and precipitation.
- **Year-wise Trends:** Changes in crop production and yield over time.
- **State-wise Comparison:** Differences in average crop yield across states.
- **Climate Analysis:** Scatter plots showing the relationship between yield and temperature, rainfall, and humidity.
- **Crop-wise Analysis:** Comparison of production across different crops.
- **Seasonal Analysis:** Differences in average yield across growing seasons.
- **Interactive Filters:** Options to explore results by state, district, crop, season, year, and soil type.

## How I Approach the Analysis

I plan to work through the project in the following stages:

1. **Data cleaning:** Check for missing values, duplicate records, inconsistent formats, and unusual values.
2. **Data validation:** Verify the units and check whether production, cultivated area, and yield are consistent.
3. **Exploratory data analysis:** Use Excel to compare crops, states, seasons, and climate variables.
4. **Dashboard development:** Use Power BI to turn the analysis into charts, KPIs, and interactive filters.
5. **Insights and interpretation:** Summarize the patterns found and explain what they might mean.

### Understanding Crop Yield

Crop yield measures how much crop is produced per unit of cultivated land.

I calculate it using:

`Yield (kg/ha) = Production (tonnes) × 1,000 / Area (ha)`

This allows me to compare productivity across records with different cultivated areas.

## What I Hope to Learn

By completing this project, I aim to improve my skills in data cleaning, exploratory data analysis, Excel, Power Query, Power BI, and communicating insights through visualizations.

I also want to understand how to interpret relationships between variables without jumping to conclusions. For example, a relationship between rainfall and crop yield does not necessarily mean that rainfall alone is responsible for changes in productivity.

## Limitations and Ethical Considerations

- **Synthetic data:** The current dataset is intended for practice and does not represent verified real-world agricultural conditions.
- **Correlation is not causation:** Climate variables may be related to crop yield, but other factors, such as irrigation, fertilizers, seeds, and farming practices, can also affect productivity.
- **Fairness:** Differences in productivity should not be used to make unsupported assumptions about smallholder farmers or rain-fed agricultural communities.
- **Data privacy:** Any future use of real farmer-level data should protect personal and identifiable information.
- **Responsible interpretation:** Any conclusions or forecasts should clearly communicate their limitations.

## Future Scope

Some improvements I would like to explore are:

- Using verified agricultural and weather datasets.
- Studying additional factors such as irrigation, fertilizer use, and soil quality.
- Comparing climate patterns and crop yields over longer periods.
- Exploring crop-yield prediction after completing the initial analysis.
- Evaluating prediction accuracy before using any model for decision-making.


## Conclusion

This project is an opportunity to apply data analytics to an area where data can support practical decisions. By exploring agricultural and climate-related variables, I aim to turn a raw dataset into an understandable dashboard and develop a clearer picture of how to analyze data, identify patterns, and communicate findings responsibly.


