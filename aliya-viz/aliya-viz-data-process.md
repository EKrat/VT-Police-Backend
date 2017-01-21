I used Excel to parse my data.

First I used the date field to extract just a year for each entry. Then I used tools like "Remove Duplicates" in excel to get an exact list of the different races listed. 

After that, I created a new sheet and used a series of "countifs" statements to identify the number of arrests per year by racial group, divided by the total number of stops for that racial group. In this phase of the analysis, I did not exclude any stops or any races.

I then looked at the how many stops by race their were, and found Native American and Unknown to be less useful to the analysis due to very small population size.

Finally, I transferred data from the Excel file into a CSV file designed to match the needs of the visualization. 
