# JSONCountries

Basic countries information in json and xml format.

<b>Countries</b> file contains the following information:

- country_code (key)
- country_name
- country_region
- country_capital 
- country_languages
- currency_name
- currency_code
- currency_symbol

<b>RegionCountriesCurrency</b> file contains the following information:

- currency_code (key)
- currency_symbol
- currency_name
- currency_region*
- countries*: array with countries that use the currency.

*When the currency is used in a single country, "currency_region" and "countries" are the same. This two types of information are useful for currencies used in more than one country. (For example: EURO -> currency_region: "Europe"; countries: "Spain, France, Germany,...".


It combines information from:
https://gist.github.com/Fluidbyte/2973986 and https://github.com/mledoze/countries
