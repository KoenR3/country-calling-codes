# Calling codes for countries

The files in this repo are based on the following and have been extended:
https://gist.github.com/adhipg/1600028

The SQL dumps have been created for MySQL but can easily be adapted for other systems.

This repo contains two files:
- **country_calling_code.sql**: Contains a list of all countries, with their iso, iso3 code and calling code
- **calling_code.sql**: The primary key is `calling_code` since several countries share a calling code.  If the country code is shared, `iso`, `iso3` are `NULL` and the `name` and `nicename` fields are the country names separated by `-`


If you wish to update this list, please submit a pull request with an explanation of the changes.  In this way we can keep one up to date list.
