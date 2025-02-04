## Data Analysis of Building Energy Benchmarking Data

### Introduction

The project involved the analysis of the Building Energy Benchmarking Dataset. The dataset provides information on the energy and greenhouse gas emission performance information for properties owned and operated by the City of Calgary.

### Methodology  
In conducting the analysis, the following approach was taken:

* **Data Cleaning and Preprocessing** \- This involved load and inspecting the dataset, handling missing data, as well as extracting and cleaning data using regular expressions. Regular expressions were used to extract numeric values from text-based numeric columns, standardize postal codes, as well as to clean and extract meaningful text from property names and addresses.
* **Exploratory Data Analysis (EDA) and Aggregations** \- This part involved generating statistical summaries, aggregations and handling outliers  
* **Data Visualization** \- Visualizations such as line charts, bar charts, and heatmaps were plotted to aid the data analysis  
* **Further Analysis** \- This section involved performing some further analysis on the dataset such as correlation analysis and hypothesis testing  
* **Reporting and Insights** \- This involved the preparation of a report which displayed key trends in energy consumption and efficiency, seasonal and property type variations, and also provided recommendations for improving energy efficiency and reducing emissions.

### Challenges Faced

Some challenges faced included the following:

* Writing regular expressions to extract numeric values from text-based numeric columns  
* Writing regular expressions to clean and extract meaningful text from addresses  
* Generating meaningful insights from the analysis performed

### Insights Gained

The following insights were gained:

* Most of the buildings had energy consumptions between 0 GJ and about 25,000 GJ, while very few buildings had energy consumptions being above 25,000 GJ.  
* Most of the energy consumption was less than 25,000 GJ, while most of the efficiencies was between 70% and 85% for consumptions less than 5,0000 GJ, with few exceptions having less than 70% or more than 85%. The very high consumptions (above 50,000 GJ) generally had higher efficiencies of 90% and above, with some exceptions having efficiencies between 60% and 90%.  
* 2019 had the highest average GHG emission, with a gradual reduction through the years. For direct GHG emissions, the average GHG emission initially reduced between 2019 and 2020\. However, the average GHG emission then went back up gradually through the remaining years. This indicates that while the direct GHG emissions rose from 2020 to 2023, the indirect GHG emissions must have reduced in those years, since there was also a reduction in total GHG emissions.  
* Distribution centers had the highest average consumption of energy. This average consumption was about 7 times more than that of fitness centers/health clubs/gyms, which had the second highest average energy consumption. The lowest average energy consumptions came from properties such as fire stations, performing arts, mixed use properties, and others.

### License

This project is licensed under the terms of the MIT license.
