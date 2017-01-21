# Calculating Searches By Race

1) Removed all rows with a blank in the "Stop Search" column, resulted in 277377 rows out of 283285 records 

2) Filtered by races (including "Unknown" race, excluding "Unused Code") to determine the number of stops per race

3) Counted number of searches per race by including "Consent Search - Probable Cause", "Consent Search - Reasonable Suspicion", "Search with Warrant", and "(Winooski) Passenger Search"

4) Calculated number of non-search stops by subtracting "number of stops - number of searches" per race