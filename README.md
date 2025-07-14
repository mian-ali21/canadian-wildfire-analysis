**Canadian Wildfire Analysis: An Evidence-Based Perspective**

**Overview**
This project provides a data-driven analysis of Canadian wildfires to understand better the causes, trends, and impact of wildfire activity. The analysis critiques media narratives, highlights the significance of natural vs. human causes, and forecasts future wildfire severity using time series methods.

The work is inspired by ongoing debates around the role of climate change in wildfire frequency and severity. Using public datasets, this project clarifies misconceptions and offers evidence-based insights.

**Objectives**
- Clean and transform wildfire datasets from Canadian public data sources
- Visualize trends in wildfire activity over time and by region
- Analyze causes (human vs. natural) and assess their impact
- Forecast future wildfire severity
- Provide actionable, data-supported conclusions

**Key Findings**
- 2023 was the most destructive wildfire year in Canada’s history (by area burned)
- Lightning is the primary driver of area burned, not human activity
- Wildfires are increasingly intense, even if frequency is stable
- Summer months (May–August) account for the majority of wildfires
- Financial losses have decreased over time, reflecting better management

**Tools & Technologies**
**Programming Language:** R

**Key Packages:**
- dplyr
- ggplot2
- forecast
- reshape2
- tidyr
- readxl
- scales

**Reporting:** RMarkdown
**Visualization:** ggplot2

**Project Structure**
canadian-wildfire-analysis/
├── notebooks/ 

│   └── wildfire-analysis.Rmd

├── report/ 

│   └── Canadian-Wildfire-Analysis-Report.docx 

├── requirements.txt 

└── README.md

**Data Sources**
- National Forestry Database (Canada): http://nfdp.ccfm.org/en/data/fires.php
- Natural Resources Canada (NBAC Fire Reports): https://cwfis.cfs.nrcan.gc.ca/downloads/nbac/

**Next Steps**
- Expand forecasting with machine learning models
- Develop interactive dashboards for public awareness
- Compare Canada’s wildfire trends with other regions (e.g., Australia, California)

**Author**
Mian Ahsan Ali
LinkedIn: https://www.linkedin.com/in/ali-021-025-mian
