# NAICSProject
link to article:
https://www.datainsightonline.com/post/analysis-of-naics-timeseries
The North American Industry Classification System (NAICS) is an industry classification system developed by the statistical agencies of Canada, Mexico, and the United States. NAICS is designed to provide common definitions of the industrial structure of the three countries and a common statistical framework to facilitate the analysis of the three economies.

	The structure of NAICS is hierarchical. The numbering system that has been adopted is a six-digit code, of which the first five digits are used to describe the NAICS levels that will be used by the three countries to produce comparable data. The first two digits designate the sector, the third digit designates the subsector, the fourth digit designates the industry group and the fifth digit designates the industry. The sixth digit is used to designate national industries. A zero as the sixth digit indicates that there is no further national detail. For example (see page 22), a 2-digit NAICS industry (e.g., 23 - Construction) is composed of some 3-digit NAICS industries (236 - Construction of buildings, 237 - Heavy and civil engineering construction, and a few more 3-digit NAICS industries). Similarly, a 3-digit NAICS industry (e.g., 236 - Construction of buildings), is composed of 4-digit NAICS industries (2361 - Residential building construction and 2362 - Non-residential building construction).

	In this blog, we take time series data analysis on the Employment data based on the North American Industry Classification System  - NAICS . Firstly, we import the data-set, prepare data and clear data. And then we take exploratory data analysis on the previous data-set.  

	The database file contain -  

Raw data: 15 CSV files beginning with RTRA. These files 	contain employment data by industry at different levels of 	aggregation; 2-digit NAICS, 3-digit NAICS, and 4-digit NAICS. 	Columns mean as follows:  	


 		(i) SYEAR: Survey Year  		

 		(ii) SMTH: Survey Month  		

 		(iii) NAICS: Industry name and associated NAICS code in the bracket 				

 		(iv) _EMPLOYMENT_: Employment


LMO Detailed Industries by NAICS: An excel file for mapping 	the RTRA data to the desired data. The first column of this file has 	a list of 59 industries that are frequently used. The second column 	has their NAICS definitions.

Data Output Template: An excel file with an empty column for 	employment
