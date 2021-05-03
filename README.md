# exploration-of-food-in-perth
Considering restaurants, is there a link between certain characteristics of eateries relative to typical socio-economic factors such as age, gender, income. 
Similarly, is a trend or representation which can be made between these eateries, socio-economic factors and other indicators such as postcodes.

To complete this analysis, we will utilise a combination of Australian Census data (https://www.abs.gov.au/census/find-census-data), Western Australia housing price sale history (https://www.kaggle.com/syuzai/perth-house-prices) and the Google Places API.

Based on the data which is available, this study will try to draw representations between factors such as the Median House Price, Median Age, Household Income and Unemployment Rates with available data through Google such as the number of restuarants within suburbs, their ratings and their price levels.

A key limitation of the this data is that the Google API has a limit on the number of results which are provided on each query. This limit is 20 results per page, and 3 pages per call. As such, this study has been limited to a maximum of 60 restuarant hits per suburb.
