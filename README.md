# NY_Broadband_Access_Model
A small Python project studying broadband availability in New York State. I utilize 2019 data from the Federal Communications Commission (FCC) on broadband deployment across the US, and 2015 US Census Bureau Cartographic Boundary files. I find that regions of higher population densities, such as New York City, Albany, and Rochester, have higher numbers of providers servicing those regions, and higher upload and download speeds. More remote regions, especially those focused primarily on agriculture, such as in the finger lakes region, have a substantially lower number of providers servicing their areas and lower internet speeds overall. The areas that have faster upload and download speeds are also where internet providers have rolled out fiber optic cable. Such a result is expected, as fiber optic cable is the considered the fastest commercially available means of wired connection, and thus, fiber optic coverage and broadband speed are expected to be positively associated with one another, thereby serving as good confirmation of our larger results. More broadly, this result may be indicative of a positive effect of competition in regions where there is a larger consumer market for broadband connection. Specifically, high density population locations where the internet market is bigger, such as in New York City, Albany, and Rochester, inevitably place more demand on broadband providers to provide better speeds, infrastructure, and services, thereby promoting competition amongst providers to offer better products to the population.

How to engage:

There are four main files:

The data file: ANES2020coded.csv \
The data codebook: ANESCodebook2022.xlsx \
The US Census Cartographic Boundary files: https://shorturl.at/lQ8Vx \ 
The primary JuPyter file: NY_Broadband_Model.py \
A short analysis: NY_Broadband_Analysis.pdf

Additional notes on the ANES 2020 data:

The variables are connected to the ANES survey in the data dictionary and the codebook for the survey is in the associated PDF. The variables have been recoded for direction and scaled to facilitate meaningful interpretations of the coefficients. You can find details of the study and a full version of the codebook at: https://electionstudies.org/project/2020-time-series-study/. The ANES study interviewed respondents in a pre-election survey that was conducted between August 18, 2020 and November 3, 2020. Election day was November 3, 2020. The study re-interviewed as many as possible of the same respondents in a post-election survey that was conducted between November 8, 2020 and January 4, 2021.
