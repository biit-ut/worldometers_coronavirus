This repository contains data scraped from https://www.worldometers.info/coronavirus/ (via http://web.archive.org/web/*/https://www.worldometers.info/coronavirus/ )

Data is in tab-separated format. Currently it covers 2020-01-29 to 2020-03-22.
Data after 2020-03-19 is straight from  https://www.worldometers.info/coronavirus/ .

`by_country` directory contains the data in files by country/territory/ship as reported on worldometers with minimal cleaning and unification applied.
`all_data.csv` contains all the currently available data in a single file.

Columns:
* timestamp - timestamp and Internet Archive id for the original file if the file was taken from the Internet Archive
* datetime  - date and time for original scraping
* country	- country/territory/ship
* TotalCases	- Extracted from "Total Cases" column or equivalent
* TotalDeaths	- Extracted from "Total Deaths" column or equivalent
* TotalRecovered	- Extracted from "Total Recovered" column or equivalent
* TotalActive	- Extracted from "Active Cases" column or equivalent
* TotalSerious	- Extracted from "Serious, Critical" column or equivalent
