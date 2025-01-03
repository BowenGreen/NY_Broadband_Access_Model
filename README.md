# NY_Broadband_Access_Model
A small Python project studying broadband availability in New York State. I utilize 2019 data from the Federal Communications Commission (FCC) on broadband deployment across the US, and 2015 US Census Bureau Cartographic Boundary files. I find that regions of higher population densities have higher numbers of providers servicing those regions and higher upload and download speeds. More remote regions, have a substantially lower number of providers servicing their areas and lower internet speeds overall. The areas that have faster upload and download speeds are also where internet providers have rolled out fiber optic cable. More broadly, these results may be indicative of a positive effect of competition in regions where there is a larger consumer market for broadband connection. High density population locations where the internet market is bigger, such as in New York City, Albany, and Rochester, inevitably place more demand on broadband providers to provide better speeds, infrastructure, and services, thereby promoting competition amongst providers to offer better products to the population.

How to engage:

There are five main files:

The US 2019 FCC data, found here: https://shorturl.at/Tqiib \
The US 2015 CB Cartographic data, found here: https://shorturl.at/lQ8Vx \
The primary python file: NY_Broadband_Model.ipynb \
A short analysis: NY_Broadband_Analysis.pdf

Additional notes on the 2015 US CB Cartographic Boundary files:

The cartographic boundary files are simplified representations of selected geographic areas from the Census Bureau’s Master Address File/Topologically Integrated Geographic Encoding and Referencing (MAF/TIGER) System. As of 2019, cartographic boundary files are available in shapefile, geodatabase, and Keyhole Markup Language (KML) format. For more details about these files, including their appropriate usage, please see the Cartographic Boundary File Description page and a full version of the codebook at: https://shorturl.at/lQ8Vx
