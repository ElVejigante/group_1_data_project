# group_1_data_project
A study about the socioeconomic impact of abandoned properties in the city of Newark




Notebook #2 (2_Newark_abandoned_data.ipynb)

For this notebook, please provide your Google.com API key as g_key in the file named api_keys.py

The Newark_abandoned_data notebook calls a JSON file from the City of Newark website obtaining a list of abandoned properties by address. (http://data.ci.newark.nj.us/dataset/abandoned-properties/resource/796e2a01-d459-4574-9a48-23805fe0c3e0)

Building DataFrames from this source allows us to utilize various functions to manipulate the data for analytical purposes.

KEY FACTORS

Translate DataFrame headers (keys) for context of the data
Build out full address including city, state, and zip code (used for next steps)

NOTE: the zip code collection for loop will run for approx. 5 minsutes before continuing to run code
--------------------------------------------------------------------------------------------------------------------
Add longitude and latitudes to the addresses for use in mapping

Additional actions
Extract the summaries by year, zip code and other useful criteria for abandoned properties on the list.  
These summaries should be compatible with other data (poverty, crime, etc.)

Map the abandoned addresses on a map of Newark, NJ
Pie plot showing the relative percentages of abandoned property by zip code