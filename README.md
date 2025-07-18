# 📊 Polish Regional Data Visualization in R

This project demonstrates how to analyze and visualize regional Polish socio-demographic data using R. It includes spatial mapping, data scraping, and statistical plots, wrapped in a final PDF report.

## 🔍 Overview

Key tasks performed in the project:

- **Map 1**: Choropleth map of divorces by voivodeship (2023) using the BDL API
- **Map 2**: Cardiovascular-related death rates per 100,000 residents in Kuyavian–Pomeranian Voivodeship
- **Plot**: Bar chart of the number of counties per voivodeship (scraped from Wikipedia)

## 🛠️ Tools & Libraries Used

- **R packages**: `sf`, `tmap`, `ggplot2`, `rvest`, `bdl`, `dplyr`, `readxl`, `stringr`
- **Data Sources**: Statistics Poland (BDL API), Wikipedia, shapefiles, Excel

## 📁 Project Files

| File | Description |
|------|-------------|
| `r_analysis_regional.Rmd` | R Markdown notebook containing all code |
| `r_analysis_regional.html` | Rendered HTML version of the notebook |
| `regional_data.pdf` | Final output report with maps and charts |
| `Dane (1).xlsx` | Excel data used for county-level analysis |
| `.RData` | Local R workspace (not required for review) |
| `.gitignore` | Prevents tracking of sensitive/local files |
| `data/` | Folder containing shapefiles used in mapping |
