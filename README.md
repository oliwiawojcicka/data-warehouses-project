## Project Topic

Analysis of pedestrian traffic in Melbourne based on data collected by the city's pedestrian sensor system.

The project includes the design and implementation of:

* a data warehouse in Microsoft SQL Server,
* an ETL process in SQL Server Integration Services,
* a galaxy schema,
* an OLAP model in Power BI,
* analytical reports and dashboards.

## Main Technologies

* Microsoft SQL Server
* SQL Server Management Studio
* SQL Server Integration Services
* Power BI
* DAX
* SQL
* Open-Meteo API

## Data Warehouse Model

The final version of the data warehouse uses a galaxy schema with three fact tables:

* `FactPedestrianCount`
* `FactWeatherHourly`
* `FactDailyTrafficSummary`

The main dimensions are:

* `DimDate`
* `DimTime`
* `DimLocation`
* `DimSensor`

The model supports analyses of pedestrian traffic by time, location, sensor, and weather conditions.
