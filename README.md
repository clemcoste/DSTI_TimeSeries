
# DSTI Examination - Time series forecasting

## Subject

![alt text]([https://github.com/clemcoste/DSTI_TimeSeries/blob/main/doc/Figure1_Elec-train-excel.png](https://github.com/clemcoste/DSTI_TimeSeries/blob/e3d33138b3f80de3f25dda837a27c2e24413f8a5/doc/Figure1_Elec-train-excel.png)?raw=true)

The file Elec-train.xlsx contains electricity consumption (kW) and outdoor air temperature for one building.
These quantities are measured every 15 minutes, from 1/1/2010 1:15 to 2/17/2010 23:45. In addition, outdoor air temperature are available for 2/18/2010. The goal is to forecast electricity consumption (kW) for 2/18/2010.
Two forecasts should be returned, in one Excel file entitled YourName.xlsx, with exactly two columns (one columns per forecast) and 96 rows:
1. The first one without using outdoor temperature,
2. The second one using outdoor temperature.
Of course, the goal is to get the best possible forecasting. So you have to test all the models we see during the course, to tune them and compare them correctly.
In addition to your forecast, you should also return a short reports (few pages), entitled YourName.pdf, explaining how you have proceeded and containing the R codes you used.
The grading will take into account:
• the quality of your methodology (40%)
• the quality of your forecast (40%)
• the quality of your report and the respect of the exam instructions (20%)

## Files details

.
├── doc                      # Examination PDF file
├── data                     # Data files
│   ├── processed            # Processed Excel data files
│   └── raw                  # Raw Excel data files
├── COSTE.pdf                # Final report in PDF
├── COSTE.xlsx               # Output data for examination - XLSX file
├── elec_forecast_Power.csv  # Output CSV - Forecast based on Power and Temp with NN
├── main.Rmd                 # R Markdown
├── main.nb.html             # R Markdown - HTML Export
└── prevHW_final.csv         # Output CSV for Multiplicative seasonal Holt-Winters

Professor : Julien JACQUES

Examination committed on Sep 29, 2022
