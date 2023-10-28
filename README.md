# OpenMeteo Weather data

Open-Meteo is an open-source weather API and offers free access for non-commercial use. 

---

API Key: No API Key Required

Website: https://open-meteo.com    

<img src="https://pbs.twimg.com/profile_images/1591121427893190664/LtkaUCDu_400x400.jpg" width="150" height="150">

---

## Project Overview

In this project the weather data for Prishtina, Kosovo is taken from OpenMeteo API. The weather data that is provided from this website are: Historical Weather data and Forecasted weather data for up to one week.

The weather its extracted with the timezone set as: **Europe/Berlin**

Columns that are extracted are:

**Datetime** <br>
**Latitude**<br>
**Longitude**<br>
**Location**<br>
**TimeZone**<br>
**Temperature(°C)**<br>
**Dewpoint(°C)**<br>
**Apparent_Temperature(°C)**<br>
**Precipitation(mm)**<br>
**Rain(mm)**<br>
**Snowfall(cm)**<br>
**Cloudcover(%)**<br>
**Windspeed(km/h)**<br>
**Winddirection(°)**<br>
**Windgusts(km/h)**<br>
**Is_day**<br>
**Shortwave_radiation(W/m²)**<br>
**Direct_radiation(W/m²)**<br>
**Direct_radiation_instant(W/m²)**<br>
**Created_Datetime**<br>


<h3>Data Sources:</h3>

* OpenMeteo API

<h3>Tools Used:</h3>

* Python
* Jupyter Notebook

<h3>Directories in this project:</h3>

* 1.Historical - The notebook of taking and storing historical weather data from the API
* 2.Forecast - The notebook of taking and storing forecast and recent weather data from the API


<h3>Operations Performed:</h3>

Firstly, in the <code>Historical</code> directory, a request for historical weather data is made from 2018 for Prishtina , the dataframe for historical values is created and then this dataframe is stored in a csv file.<br>

After that, in the <code>Forecasted</code> directory, a request for recent weather and forecasted weather data is done for Prishtina, the dataframe for forecasted values is created and then this dataframe is stored in a csv file.

---

Endrit Mustafa
