Workforce Management Information
================================

This repo contains code for processing, analysing and visualising UK government departments' Workforce Management Information returns.

The latest data and analysis are available at http://www.instituteforgovernment.org.uk/publication/civil-service-workforce

The input is a long-form CSV data file with all the departmental returns.

* The original data comes from [data.gov.uk](http://data.gov.uk) or [gov.uk](http://gov.uk).
* It contains information on the numbers of staff permanent and temporary staff and staff costs, broken down in various ways
* It is management information - not official statistics. 
* Some obvious data entry errors were corrected manually
* some errors remain, especially in the cost data

Some of the scripts rely on custom functions and data stored in the ```pbtools``` R package, which can be installed like so:

```
install.packages('devtools')
library(devtools)
install_github('petrbouchal/pbtools')
```
