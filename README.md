# NY_Broadband_Access_Model
A small Python project studying broadband availability in New York State. I utilize 2019 data from the Federal Communications Commission (FCC) on broadband deployment across the US, and 2015 US Census Bureau Cartographic Boundary files. I find that regions of higher population densities, such as New York City, Albany, and Rochester, have higher numbers of providers servicing those regions, and higher upload and download speeds. More remote regions, especially those focused primarily on agriculture, such as in the finger lakes region, have a substantially lower number of providers servicing their areas and lower internet speeds overall. The areas that have faster upload and download speeds are also where internet providers have rolled out fiber optic cable. Such a result is expected, as fiber optic cable is the considered the fastest commercially available means of wired connection, and thus, fiber optic coverage and broadband speed are expected to be positively associated with one another, thereby serving as good confirmation of our larger results. More broadly, this result may be indicative of a positive effect of competition in regions where there is a larger consumer market for broadband connection. Specifically, high density population locations where the internet market is bigger, such as in New York City, Albany, and Rochester, inevitably place more demand on broadband providers to provide better speeds, infrastructure, and services, thereby promoting competition amongst providers to offer better products to the population.

How to engage:

There are four main files:

The data file: ANES2020coded.csv \
The data codebook: ANESCodebook2022.xlsx \
The primary Python file: FauciModel.Rmd \
A short analysis: NY_Broadband_Analysis.pdf

