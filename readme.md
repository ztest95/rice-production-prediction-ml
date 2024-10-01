# Rice Production Prediction

Project files for a study on using machine learning to predict rice production, the filipino staple food of the Philippines. The study explores the relationship between climate variables and rice yields, using regression and time series forecasting models. PyCaret, an open-source Python library, was utilized to automate model selection and comparison, with the Extra Trees Regressor identified as the best-performing model. Climate forecasts were integrated into the models to predict future rice production over a six-year period, providing insights into how seasonal climate variations affect both irrigated and rainfed rice crops.

## Data

The study utilizes two main datasets: 
1. Climate Data: 
- Requested from PAGASA (Philippine Atmospheric, Geophysical, and Astronomical Services Administration). [***](https://www.pagasa.dost.gov.ph/climate/climate-data)
- Includes 10 years of monthly data (2013-2022) from 11 weather stations across Northern and Central Luzon.
- Variables: Minimum Temperature (TMIN), Maximum Temperature (TMAX), Rainfall (RF), Relative Humidity (RH), and Wind Speed (WS).
!All

> [!NOTE] 
> Most notebook outputs are cleared as they expose information from the climate data

2. Rice Production Data:
- Retrieved from the Philippine Statistics Authority (PSA) OpenStat database. [***](https://openstat.psa.gov.ph/PXWeb/pxweb/en/DB/DB__2E__CS/0012E4EVCP0.px/table/tableViewLayout1/?rxid=bdf9d8da-96f1-4100-ae09-18cb3eaeb313)
- Covers quarterly rice production volumes for irrigated and rainfed rice ecosystems from 2013 to 2022 in Northern and Central Luzon.

## Notebooks

- `1_climate.ipynb`: Processes climatological data.
- `2_rice.ipynb`: Processes rice production data.
- `3_merge_datasets.ipynb`: Merges climate and rice datasets.
- `4_analysis_irrice.ipynb`: Analyzes irrigated rice production.
- `5_analysis_rarice.ipynb`: Analyzes rainfed rice production.
- `6_climate_forecasts.ipynb`: Generates climate forecasts.
- `7_ricepred_irrigated.ipynb`: Predicts irrigated rice production.
- `8_ricepred_rainfed.ipynb`: Predicts rainfed rice production.
- `forecast_plot.ipynb`: Forecasts Rice Production.
- `manual_adaboost.ipynb`: Manual implementation of AdaBoost.
- `manual_lr.ipynb`: Manual implementation of Linear Regression.
- `map_stations.ipynb`: Maps weather stations.

## Contributors

- [ztest95](https://github.com/ztest95)
- [dnzldotexe](https://github.com/dnzldotexe)

## Discussion

For comments, feel free to use the discussion section.