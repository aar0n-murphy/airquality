# airquality

File “data.csv” contains the levels of fine dust (PM10) as an average daily value, for different locations around Amsterdam. The measurements are in micrograms per cubic meter. 

The measurements are classified by year (year_2015, year_2016…) and by location. Each location has a code (measurement_code), which is allocated to each location in the file “location_data.csv”.

The data is retrieved from https://www.luchtmeetnet.nl from the Reports section.
The relevant query fields are filled in as such:
	•	Component: PM10
	•	Report: mean_year_day
	•	Period: 2015-2021

Only data from the GGD is retained. 
