---
layout: haha
title: Hack Harris Resources
---

Suggested datasets from the [Chicago data portal](http://data.cityofchicago.org):

* [Crime reports in Chicago, August 2014](/resources/haha/crimes_2001_to_present_2014-09-03.csv)
    * You may need to reduce the number of columns and/or rows to fit it into CartoDB
    * Good variables to cluster on: `primary_type`, `arrest`, `location_description`
* [Food inspections in Chicago, 2014 to date](/resources/haha/food_inspections_2014-09-03.csv)
    * You will need to reduce the size to fit it into CartoDB
    * Interesting variables to use: `facility_type`, `risk` (predicted risk of failing inspection), `results`
* [New businesses in Hyde Park and surrounding neighborhoods, 2014 to date](/resources/haha/business_licenses_2014-09-03.csv)
    * Very few records
    * Can you say something interesting about where they're opening?
* [Rats spotted in Hyde Park and surrounding neighborhoods, 2014 to date](/resources/haha/311_service_requests_rodent_baiting_2014-09-03.csv)
    * Also very few cases (thankfully)
    * Can you show something interesting? In how many places did they bait for rats?
