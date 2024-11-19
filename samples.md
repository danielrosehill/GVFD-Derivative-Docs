---
title: Sample Data
---

*Note: Afghanistan is the first country in the [territories list](/geo/territories) ordered alphabetically so is chosen to demonstrate geographically-stratified examples*

## Air Pollution: PM 2.5 Values By Country 

This `JSON` array - from V1 of the [derivative dataset](https://github.com/danielrosehill/Global-Value-Factors-Explorer/tree/main/Data/GVFD-Deriv/data) presents the value factors for particulate matter 2.5 (PM2.5). 

Details of the air pollution dataset can be found [here](specs/airpollution). 

The value factors (`value:` in the array) are denominated in US dollars. The quantitative environmental parameters is `metric tons` of measured PM2.5 release.

This value factor is stratified by location.

```json
{
    "PM2.5": {
        "Afghanistan": [
            {
                "Category": "PM2.5",
                "Location": "Urban",
                "Impact": "Primary Health",
                "Units": "/metric ton",
                "Reference": "Air Pollution_PM2.5_Urban_Primary Health",
                "Value": "40,495.28"
            },
            {
                "Category": "PM2.5",
                "Location": "Peri-Urban",
                "Impact": "Primary Health",
                "Units": "/metric ton",
                "Reference": "Air Pollution_PM2.5_Peri-Urban_Primary Health",
                "Value": "34,468.58"
            },
            {
                "Category": "PM2.5",
                "Location": "Rural",
                "Impact": "Primary Health",
                "Units": "/metric ton",
                "Reference": "Air Pollution_PM2.5_Rural_Primary Health",
                "Value": "19,386.52"
            },
            {
                "Category": "PM2.5",
                "Location": "Transport",
                "Impact": "Primary Health",
                "Units": "/metric ton",
                "Reference": "Air Pollution_PM2.5_Transport_Primary Health",
                "Value": "31,346.36"
            },
            {
                "Category": "PM2.5",
                "Location": "N/A for PM2.5",
                "Impact": "Visibility",
                "Units": "/metric ton",
                "Reference": "Air Pollution_PM2.5_N/A for PM2.5_Visibility",
                "Value": "4.78"
            }
        ]
    }
}
```
