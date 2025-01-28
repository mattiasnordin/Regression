# Data on Swedish municipalities, 2022

**Name**: ```municip_data22```

**Description**: A cross-section of data for the 290 Swedish municipalities for the year 2022.

**Source**: Most of the data come from Statistics Sweden's Statistical database (https://www.statistikdatabasen.scb.se/pxweb/en/ssd/). Data on political coalitions at the municipal level come from the Swedish Association of Local Authorities and Regions (https://catalog.skl.se/catalog/1/datasets/27). Data have been processed by the R package author and neither Statistics Sweden nor the Swedish Association of Local Authorities and Regions bear any responsibility for the final data.

**Variable list**:
-```municip_code```: Municipal code number.
-```municip_name```: The name of the municipality.
-```county_code```: County code number. 
-```year```: Year.
-```pop```: The population size on the 31st of December 2021. Hence, the population value for 2022 corresponds to the population size on December 31st 2021.
-```share0_19```: The share of the population on the 31st of December 2021 that are aged 0-19.
-```share75_```: The share of the populationy on the 31st of December year 2021 that are aged 75+.
-```share_elementary_school```: The share of the population aged 16-74 with primary school education as highest education on the 31st of December 2021. The population excludes individuals where information about education level is missing.
-```share_secondary_school```: The share of the population aged 16-74 with secondary school education as highest education on the 31st of December 2021. The population excludes individuals where information about education level is missing.
-```share_tertiary_school```: The share of the population aged 16-74 with tertiary education as highest education on the 31st of December 2021. The population excludes individuals where information about education level is missing.
-```tax_rate```: The municipal tax rate for 2022.
-```tax_rate_4_years_back```: The municipal tax rate for 2018.
-```tax_base```: The tax base per inhabitant in SEK according to taxation at 2022, referring to incomes during 2021.
-```expenditures```: The municipal expenditure per inhabitant in SEK for 2022.
-```real_tax_base```: The variable "tax_base" deflated to 2023 prices.
-```real_expenditures```: The variable "expenditures" deflated to 2023 prices.
-```share_votes_left_last_election```: Share of votes to the municipal council that were cast to one of the three parties Miljöpartiet, Socialdemokraterna or Vänsterpartiet at the election 2018.
-```share_seats_left_last_election```: Share of seats in the municipal council for the three parties Miljöpartiet, Socialdemokraterna or Vänsterpartiet after the election 2018.
-```nr_seats_council```: Number of seats in the municipal council after the election 2018.
-```coalition_last_term```: The type of ruling coalition after the election 2018 according to the Swedish Association of Local Authorities and Regions. The categories are V (left-wing coalition), B (right-wing coalition), Bl (mixed coalition), A ("Alliance": the four parties Centerpartiet, Kristdemokraterna, Liberalerna and Moderaterna) and Ö (other).
-```left_coalition_last_term```: An indicator for if the variable "coalition_last_term" takes a value of "V" or not.
