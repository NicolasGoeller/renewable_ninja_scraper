########## Webscraper for Renewables.Ninja #####################

This project archives the functions and scripts to utilize webscraping on a large scale
for the API provided by Renewables.Ninja (https://www.renewables.ninja/). The underlying 
approaximation procedure was first conducted by Behrang Shirizadeh (https://github.com/BehrangShirizadeh)..

The python file in this project has (most) necessary functions and inputs to automate the
retrieval of data from said website, tailored for the purpose of energy systems modelling
projects at CIRED, Paris (specifically the Eoles model):
- renewables_ninja_functions: Contains all basic functions for retrievels and helpers for
that purpose.
- renewables_parallel: Contain a routine for parallelisation of said functions if number 
of requests is very high (most likely for country-based approximations over many years).
- inputs: folder with baseline coordinates and capacity weights to be used (as taken from 
https://github.com/BehrangShirizadeh/VRE_locations).
- ninja_accounts_template: template file for teh accounts that provide tokens for the 
scraping process. Full account file available for CIRED users upon request (by mail).