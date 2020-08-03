# Freight Rate Dynamic Pricing Dashboard

It is an interactive dashboard for port to port freight rate dynamic pricing.

# Platform

Dashboard can be accessed at <a href="https://ischa.co/dynamic-pricing-dashboard/">here</a>. Rate estimation table can be copied, perinted or saved as CSV, or Excel file.

# Model

Model consists of 

- [x] Collecting external data 
- [x] Historical data 
- [x] Mathematical modeling 
- [x] Machine Learning Algorithm

and is built with <a href="https://www.knime.com/">Knime</a> (open-source data analytics platform).

After data collection, preparation, and analysis, the optimum dynamic rates are calculated for each shipping route and load type (e.g. container 20, 40, 40HC, and 45HC) for the coming week.

Currently, Singapore to Europe (7 ports) and vise versa are included in the model.

# Built with
<a href="https://www.knime.com/">Knime</a>

1. Download Knime from https://www.knime.com/downloads
2. Unzip "KNIME_Project_O3_ISCHA 1.zip" 
3. Open Knime and then File> import workflow > open "KNIME_Project_O3_ISCHA 1.knwf" file

you will see the workflow:

![Workflow](https://github.com/ishcha-o3/O3-Challenge-Dynamic-Pricing/blob/master/workflow.png)

## Data

Sample data is also included in the zip file ("Data" Folder).
