
# DSTI Examination - Time series forecasting

## Subject

![Figure 1](https://github.com/clemcoste/DSTI_TimeSeries/blob/main/doc/Figure1_Elec-train-excel.png)

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

.<br />
├── doc&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; # Examination PDF file<br />
├── data&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# Data files<br />
&ensp;│&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;├── processed&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# Processed Excel data files<br />
&ensp;│&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;└── raw&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# Raw Excel data files<br />
├── COSTE.pdf&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# Final report in PDF<br />
├── COSTE.xlsx&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# Output data for examination - XLSX file<br />
├── elec_forecast_Power.csv&ensp;&ensp;# Output CSV - Forecast based on Power and Temp with NN<br />
├── main.Rmd&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# R Markdown<br />
├── main.nb.html&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# R Markdown - HTML Export<br />
└── prevHW_final.csv&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# Output CSV for Multiplicative seasonal Holt-Winters<br /><br />

Professor : Julien JACQUES<br /><br />

Examination committed on Sep 29, 2022
