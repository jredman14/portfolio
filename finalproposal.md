# Final Project Part 1
For this assignment, I proposed a topic for my final project in Telling Stories with Data. Below, you'll find a summary of my proposal, an outline of my project, the data sources I plan to use in various visualizations, rough sketches of said visualizations, and my initial idea for how I will compile and present my project.

# Summary
Being a northern Virginia native, I’ve watched my home area grow and change for roughly two decades now. Whether it be as small as the county building a bike lane connecting my community to a shopping center, or as large as the intense development near the western urban fringe, northern Virginia is a dynamic, thriving suburb in many ways. But the suburban way of life — with its car-centric infrastructure, fertilized green lawns, sprawling infrastructure, and deeply Euclidian zoning — feels like the antithesis of sustainability. And given that the cost of living has risen substantially over the years, it’s fair to wonder whether the current development patterns are meeting the needs of residents. 

More generally, I want to explore the overall health of northern Virginia as a region, so I obtained several datasets from the U.S. Census Bureau, Federal Reserve Bank of St. Louis, and Esri that show various measures that together, I believe can paint a detailed and nuanced picture of the area’s urban fabric. I chose datasets representing the main counties that make up the area: Fairfax, Arlington, Loudoun, and Prince William. 

# Outline
Overall, I want to begin with the more positive metrics, then transition to metrics that paint a less rosy picture, before ending with my final sobering point and suggestions for the future. An overview of the structure is below:

**The overall population continues to grow, across the area, especially in outlying Loudoun and Prince William Counties.**

	Data sources

	o U.S. Census Bureau, Resident Population in Fairfax County, VA [VAFAIR5POP], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/VAFAIR5POP, February 11, 2024.
	
	o U.S. Census Bureau, Resident Population in Arlington County, VA [VAARLI0POP], retrieved from FRED, Federal Reserve Bank of St. Louis; 	
 		https://fred.stlouisfed.org/series/VAARLI0POP, February 11, 2024.
	
	o U.S. Census Bureau, Resident Population in Loudoun County, VA [VALOUD5POP], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/VALOUD5POP, February 11, 2024.
	
	o U.S. Census Bureau, Resident Population in Prince William County, VA [VAPRIN3POP], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/VAPRIN3POP, February 11, 2024.

**The area remains very wealthy, with each county having a median household income of over $100,000.**

	Data sources
	
	o U.S. Census Bureau, Estimate of Median Household Income for Fairfax County, VA [MHIVA51059A052NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/MHIVA51059A052NCEN, February 11, 2024.
	
	o U.S. Census Bureau, Estimate of Median Household Income for Arlington County, VA [MHIVA51013A052NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/MHIVA51013A052NCEN, February 11, 2024.
	
	o U.S. Census Bureau, Estimate of Median Household Income for Loudoun County, VA [MHIVA51107A052NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/MHIVA51107A052NCEN, February 11, 2024.
	
	o U.S. Census Bureau, Estimate of Median Household Income for Prince William County, VA [MHIVA51153A052NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/MHIVA51153A052NCEN, February 11, 2024.

**However, poverty has remained stagnant, overall, and has seen periodic increases over the years.**

	Data sources
	
	o U.S. Census Bureau, Estimated Percent of People of All Ages in Poverty for Fairfax County, VA [PPAAVA51059A156NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/PPAAVA51059A156NCEN, February 11, 2024.
	
	o U.S. Census Bureau, Estimated Percent of People of All Ages in Poverty for Arlington County, VA [PPAAVA51013A156NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/PPAAVA51013A156NCEN, February 11, 2024.
	
	o U.S. Census Bureau, Estimated Percent of People of All Ages in Poverty for Loudoun County, VA [PPAAVA51107A156NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/PPAAVA51107A156NCEN, February 11, 2024.
	
	o U.S. Census Bureau, Estimated Percent of People of All Ages in Poverty for Prince William County, VA [PPAAVA51153A156NCEN], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/PPAAVA51153A156NCEN, February 11, 2024.

**Home ownership rate has lagged behind (though Prince William is seeing a positive trend).**

	Data sources
	
	o U.S. Census Bureau, Homeownership Rate (5-year estimate) for Fairfax County, VA [HOWNRATEACS051059], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/HOWNRATEACS051059, February 11, 2024.
	
	o U.S. Census Bureau, Homeownership Rate (5-year estimate) for Arlington County, VA [HOWNRATEACS051013], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/HOWNRATEACS051013, February 11, 2024.
	
	o U.S. Census Bureau, Homeownership Rate (5-year estimate) for Loudoun County, VA [HOWNRATEACS051107], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/HOWNRATEACS051107, February 11, 2024.
	
	o U.S. Census Bureau, Homeownership Rate (5-year estimate) for Prince William County, VA [HOWNRATEACS051153], retrieved from FRED, Federal Reserve Bank of St. 
 		Louis; https://fred.stlouisfed.org/series/HOWNRATEACS051153, February 11, 2024.

**And the number of building permits for housing has decreased in many areas, especially in Fairfax and Prince William Counties.**

	Data sources
	
	o U.S. Census Bureau, New Private Housing Structures Authorized by Building Permits for Fairfax County, VA [BPPRIV051059], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/BPPRIV051059, February 11, 2024.
	
	o U.S. Census Bureau, New Private Housing Structures Authorized by Building Permits for Arlington County, VA [BPPRIV051013], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/BPPRIV051013, February 11, 2024.
	
	o U.S. Census Bureau, New Private Housing Structures Authorized by Building Permits for Loudoun County, VA [BPPRIV051107], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/BPPRIV051107, February 11, 2024.
	
	o U.S. Census Bureau, New Private Housing Structures Authorized by Building Permits for Prince William County, VA [BPPRIV051153], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/BPPRIV051153, February 11, 2024.

**The areas continue to be largely car dependent, especially outside of Arlington County.**

	Data sources
	
	o U.S. Census Bureau. "Commuting Characteristics by Sex." American Community Survey, ACS 5-Year Estimates Subject Tables, Table S0801, 2022, 
 		https://data.census.gov/table/ACSST5Y2022.S0801?q=s0801&g=050XX00US51013,51059,51107,51153. Accessed on February 12, 2024.
	
**And, save for a recent decline (perhaps attributable to remote work), commute times have increased over the years.**

	Data sources
	
	o U.S. Census Bureau, Mean Commuting Time for Workers (5-year estimate) in Fairfax County, VA [B080ACS051059], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/B080ACS051059, February 11, 2024.
	
	o U.S. Census Bureau, Mean Commuting Time for Workers (5-year estimate) in Arlington County, VA [B080ACS051013], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/B080ACS051013, February 11, 2024.
	
	o U.S. Census Bureau, Mean Commuting Time for Workers (5-year estimate) in Loudoun County, VA [B080ACS051107], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/B080ACS051107, February 11, 2024.
	
	o U.S. Census Bureau, Mean Commuting Time for Workers (5-year estimate) in Prince William County, VA [B080ACS051153], retrieved from FRED, Federal Reserve Bank of St. Louis; 
 		https://fred.stlouisfed.org/series/B080ACS051153, February 11, 2024.

**The increase in commute times and car dependence of the area is made apparent by the growth of impervious surfaces in the past couple decades, which shows significant urban sprawl.**

	Data sources
	
	o USA NLCD Impervious Surface Time Series. USGS, ESRI, 
 		https://www.arcgis.com/home/item.html?id=1fdbb561c58b45c58f8f966c00c78ae6. Accessed 12 Feb. 2024.
	
	o County Polygon. Arlington County, Virginia GIS Open Data, 
 		https://gisdata-arlgis.opendata.arcgis.com/datasets/c8b70c8f91a24926aa874802165e0172_0/explore. Accessed 12 Feb. 2024.
	
	o Fairfax County Boundary. Fairfax County GIS & Mapping Services Open Data Site, 
 		https://data-fairfaxcountygis.opendata.arcgis.com/datasets/e6e10e55d29642238d4d03b1a4a11b09_0/explore. Accessed 12 Feb. 2024.
	
	o Jurisdictions. GIS Data Portal for Prince William County, Virginia, 
 		https://gisdata-pwcgov.opendata.arcgis.com/datasets/26e0c74d4fe845d7a5871c0747e6e74f_19/explore. Accessed 12 Feb. 2024.
	
	o Loudoun County Boundary. Loudoun County GeoHub and Open Data, 
 		https://geohub-loudoungis.opendata.arcgis.com/datasets/cd56614ff14f44fb82f50a8baf427125_0/explore. Accessed 12 Feb. 2024.

Overall, based on the data, it’s fair to wonder whether the Northern Virginia area is providing a **quality built environment** within its population centers to support **sustainable lifestyles** and prevent the area from sprawling out further. **Infill development to increase density** within the current suburban footprint could help support the area’s future.

# Data Usage and Sketches

![image](https://github.com/jredman14/portfolio/assets/156849712/e64af56a-2d7f-41fd-9c87-2c4a49713377)

![image](https://github.com/jredman14/portfolio/assets/156849712/04f78b18-965b-4388-8320-af0e0115bc9a)

I want to use the datasets from the Census and from the Federal Reserve Bank of St. Louis to create line graphs to show the trends over time, comparing values from the different counties (population, income, poverty, home ownership, building permits, car usage, commute times), and perhaps including a line on each graph representing the total trend (by creating a “Sum” or "Mean" column for each year in my spreadsheet files, where applicable). In Figures 1 and 2 above, you'll see examples of what those line graphs will look like, with one example showing an "average" line (a good fit for an income graph, for example) and another showing a "sum" line (a good fit for a metric like building permits issued). 

![image](https://github.com/jredman14/portfolio/assets/156849712/c20059b3-ef7a-4475-ab8a-562dae63d47d)

The USA NLCD Impervious Surface Time Series from ESRI and the USGS shows the impervious surface cover across America over time (with a slider that allows the viewer to see the impervious cover between the years 2001 to 2021), and I plan on using the county boundary feature classes I downloaded from the county GeoHubs to show the impervious surface cover within the “study area” (Fairfax, Prince William, Arlington, and Loudoun Counties). Figure 3 above shows a rough approximation of what I expect this map to look like (I would also use a street basemap to capture some of the growth around corridors). 

Taken together, I believe that this collection of visuals will help support my story structure I outlined above, showing Northern Virginia to be an area that needs to rethink its development patterns to meet the needs of its present and future residents. 

# Method
I believe that using Shorthand and Tableau will be best for my project, since I’ll easily be able to embed my data visualizations. While ArcGIS StoryMaps might make for a slightly better interactive map with the impervious surface (and give the user the ability to adjust the map themselves), however (to my knowledge) StoryMaps does not support HTML code, which would make it more difficult to have high quality data visualizations. 
