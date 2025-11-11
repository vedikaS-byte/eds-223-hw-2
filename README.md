# Exploring Patterns of Environmental Justice in Los Angeles County

## Description

With an estimated 9.8 million residents in 2023, Los Angeles County is the most populous county in California and the entire United States (Data USA, n.d.). Los Angeles County is also racially diverse, with approximately 2.48 million White (non-Hispanic) residents, 2.26 million Hispanic residents, 1.4 million Asian residents, and 743,000 Black residents (Data USA, n.d.). The city has a rich history and is culturally diverse; however, marginalized communities continue to face disproportionate environmental, social, and economic burdens.

Environmental injustices experienced by marginalized communities are interconnected with patterns of reduced biodiversity in urban environments. The Home Owners’ Loan Corporation (HOLC) created a neighborhood ranking system to guide mortgage lending decisions, classifying areas from A (green) to D (red) based on perceived neighborhood safety (Oliver, 2025). This system was later used to deny home loans and other financial opportunities to residents in lower-rated neighborhoods, which were often predominantly inhabited by people of color (Oliver, 2025). This practice is known as "redlining", defined as the process of refusing financial support to a community based on discriminatory practices (Merriam-Webster Legal, n.d.). Reduced biodiversity in redlined neighborhoods is also a concern, as these areas tend to face increased heating from impervious cover and reduced greenery (Hoffman et al., 2020).

The purpose of this analysis is to examine how historical redlining in Los Angeles has influenced communities in terms of environmental and socioeconomic conditions. Additionally, the analysis investigates how biodiversity, measured by recorded bird observations, is affected in historically redlined neighborhoods.

## Directory Contents

This repository contains:

```         
EDS223-HW2
│   README.md
│   eds-223-hw2.qmd
│   eds-223-hw2.pdf
│   eds-223-hw-2.Rproj
│   figs
│   └───Heatmap_Mean_EJScreen_Indicators_by_HOLC_Grade.png
│   └───LA_HOC.png
│   └───Mean_EJScreen_Indicators_by_HOLCGrade.png
│   └───Percent_of_Bird_Observations_in_Redlined_Neighborhoods_Within_HOLC_Grades.png
│
└───.gitignore
     └───data
         └───ejscreen
         └───gbif-birds-LA
         └───mapping-inequality
```

## Data Description and Access

The Environmental Justice Mapping and Screening Tool was created by the Environmental Protection Agency (EPA) to track and reveal environmental injustices based on several socioeconomic variables. The dataset was downloaded from the [EPA website](https://www.epa.gov/ejscreen/download-ejscreen-data) and contains environmental and demographic data at the block group level.

The University of Richmond’s Digital Scholarship Lab provides digitized HOLC maps and associated spatial and attribute data on inequality through its *Mapping Inequality* project. This analysis utilized HOLC grade designations specific to Los Angeles, downloadable from the [project website](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads) (Oliver, n.d.). Additional information regarding metadata can be referenced [here](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads).

The [Global Biodiversity Information Facility](https://eds-223-geospatial.github.io/assignments/gbif.org) provides aggregated data on species biodiversity and serves as the world’s largest open-access biodiversity database. Each observation in the database generally includes a location and the date on which the species was recorded (Oliver, n.d.). Bird biodiversity observations for 2021-2023 were derived from the database for Los Angeles.

## Author Contributors

This repository and analysis was compiled by Vedika Shirtekar. All datasets and assignment instructions were provided by The Bren School of Environmental Science and Management, UC Santa Barbara for the MEDS program.

## Citations

Connolly, N. D. B., Winling, L., Nelson, R. K., & Marciano, R. (2018). Mapping inequality. In The Routledge Companion to Spatial History (pp. 502–524). Routledge. <https://doi.org/10.4324/9781315099781-29>

Definition of redlining. (n.d.). Merriam-Webster Legal. Retrieved October 19, 2025, from <https://www.merriam-webster.com/legal/redlining>

Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nature Human Behaviour, 7(11), 1869–1877. <https://doi.org/10.1038/s41562-023-01688-5>

Hoffman, J. S., Shandas, V., & Pendleton, N. (2020). The effects of historical housing policies on resident exposure to intra-urban heat: A study of 108 US urban areas. Climate, 8(1), 12. <https://doi.org/10.3390/cli8010012>

Leaflet provider demo. (n.d.). Retrieved October 19, 2025, from <https://leaflet-extras.github.io/leaflet-providers/preview/>

Los angeles county, CA. (n.d.). Data USA. Retrieved October 19, 2025, from <https://datausa.io/profile/geo/los-angeles-county-ca>

Mapping inequality. (n.d.). Retrieved October 19, 2025, from <https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads>

Oliver, R. (n.d.). Homework assignment 2. Retrieved October 19, 2025, from <https://eds-223-geospatial.github.io/assignments/HW2.html>
