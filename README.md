# The Blue Sky (Theme 2)
Monitoring air quality in various cities across the globe is becoming an utmost necessity as air pollution can lead to several respiratory/cardiovascular diseases. As per reports from WHO, more than 7 million mortalities have been recorded worldwide due to diseases related to air pollution. Increasing urbanisation and industrialisation have a negative impact on air quality which is already alarming in many cities across the world. In practice, the installation of ground stations for local air quality measurement would not be a feasible solution. A mobile application in this regard would enable us to make an informed decision.
<h2><b>Goal</b>: Forecasting Sensor Measurements in Smart Air Aquality Monitoring System</h2>

# Problem Statement: 

A number of factors in the air can have an impact on its quality. Multiple sensors monitoring various parameters are used in air quality monitoring sensing systems, which are available as a whole suite. The role of temperature  and carbon monoxide in air quality is vital. The following issue that may be addressed via this hackathon in order to make such systems smarter:
# Dataset:
https://www.kaggle.com/fedesoriano/air-quality-data-set?select=AirQuality.csv
# Dataset Information
The dataset contains 9357 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level,within an Italian city. Data were recorded from March 2004 to February 2005 (one year) representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer. Evidences of cross-sensitivities as well as both concept and sensor drifts are present as described in De Vito et al., Sens. And Act. B, Vol. 129,2,2008 (citation required) eventually affecting sensors concentration estimation capabilities. Missing values are tagged with -200 value.
This dataset can be used exclusively for research purposes. Commercial purposes are fully excluded.
# Attribute Information
</br>0 Date (DD/MM/YYYY)
</br>1 Time (HH.MM.SS)
</br>2 True hourly averaged concentration CO in mg/m^3 (reference analyzer)
</br>3 PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
</br>4 True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
</br>5 True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
</br>6 PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
</br>7 True hourly averaged NOx concentration in ppb (reference analyzer)
</br>8 PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
</br>9 True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
</br>10 PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
</br>11 PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
</br>12 Temperature in Â°C
</br>13 Relative Humidity (%)
</br>14 AH Absolute Humidity
# Models Trained On
Linear Regression
