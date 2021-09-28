# WeatherToFlood
A repository to investigate weather data in relationship to the floods in Germany (07/2021)

The repo contains the used data in the Data folder (including description for the stations and historical data for three stations)
The notebook DecriptionProcessing is used for finding relevant weather stations that are near to the area, but can also be used to get further information on the weather station.

The main analysis is contained in the WeatherDataAnalysis notebook. The notebook contains comments about the data and the analysis. For a more comprehensive anlysis please refer to
the following [medium post](https://medium.com/@qdxNHG/this-is-why-the-flood-in-germany-was-not-so-unexpectable-95f7058b93b6).

## Results
The analysis showed the following:
- There was a trend leading up to the year 2021 where temperature rose
- There was a trend leading up to the year 2021 where the percipitation decreased drasticly
- There is almost no correlation between temperature and percipitation on a local level
- Therefore a simple forecast doesn't yield good results

## Libraries
- pandas
- numpy
- seaborn
- sci-kit learn

## Acknowledgement
Dataset: DWD historical montly data & DWD recent daily data source: (DWD)[https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/daily/kl/]

