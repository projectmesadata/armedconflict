# Armed Conflict Data

### About

The data pipeline in this repository is intended for model validation. For example, if someone is making a civil violence model for a specific country or specific group, the enclosed data pipelines can help them validate their model by geolocation of events and/ or by time series of the number of attacks.  

### Data

The data used is from the Armed Conflict Location Event Data (ACLED). 

"The Armed Conflict Location & Event Data Project (ACLED) is a disaggregated data collection, analysis, and crisis mapping project. ACLED collects the dates, actors, locations, fatalities, and types of all reported political violence and protest events across Africa, the Middle East, Latin America & the Caribbean, East Asia, South Asia, Southeast Asia, Central Asia & the Caucasus, Europe, and the United States of America. The ACLED team conducts analysis to describe, explore, and test conflict scenarios, and makes both data and analysis open for free use by the public."

"ACLED is a registered non-profit organization with 501(c)(3) status in the United States."

Copied from [about ACLED](https://acleddata.com/about-acled/)

### ACLED Registration

Users can test and use the notebook using the Google Colab badge. Although to download data users will need to get an ACLED API Key and Email, instructions are located on the ACLED registration at [ACLED](https://acleddata.com/register/)

### Repository Files 

* ACLED Data Download builds and executes the API request and then retrieves a comma seperated value (.csv) file.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/projectmesadata/armedconflict/blob/main/ACLED_Data_Download.ipynb)

* ACLED Interactive allows users to upload a downloaded .csv and select parameters to map and see over a time series.  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/projectmesadata/armedconflict/blob/main/ACLED_Interactive.ipynb)



