| [Home](https://jredman14.github.io/portfolio) | [Critique by Design](athletes) | [Final Project 1](finalproposal) | [Final Project 2](finalwireframe) | [Final Project 3](finalproject) |

# Visualizing government debt using Tableau
In this exercise, I used data from the [Organisation for Economic Co-operation and Development (OECD)](https://data.oecd.org/gga/general-government-debt.htm) to display government debt-to-GDP ratios of various OECD member states between 1995 and 2022. The following visualizations show this data as a bar chart for the most recent year, as a heat map showing each country's ratio over time, and as box-and-whisker plots by country, showing the range of ratios within the timeframe. 

Source: OECD (2024), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 29 January 2024)

# Government debt bar chart
<iframe src="https://data.oecd.org/chart/7kjp" width="1000" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7kjp" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2015</a></iframe>

# Government debt heat map
<div class='tableauPlaceholder' id='viz1706431922514' style='position: relative'><noscript><a href='#'><img alt='Government Debt-to-GDP Ratio Over Time, 1995-2022 (Source: OECD) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt_17064318793230&#47;GovernmentDebt-to-GDPRatioOverTime1995-2022SourceOECD&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebt_17064318793230&#47;GovernmentDebt-to-GDPRatioOverTime1995-2022SourceOECD' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt_17064318793230&#47;GovernmentDebt-to-GDPRatioOverTime1995-2022SourceOECD&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1706431922514');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Government debt box-and-whisker plot
<div class='tableauPlaceholder' id='viz1706561769928' style='position: relative'><noscript><a href='#'><img alt='Range of Government Debt-to-GDP Ratios by Country, 1995-2022 (Source: OECD) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-myversion&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebt-myversion&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebt-myversion&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1706561769928');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Discussion
The bar chart was a very clean way to display the difference between countries' debt-to-GDP ratio for a single year, however, attempting to compare multiple years between countries (such as with a clustered bar chart) would have gotten unwieldy. The heat map solved that issue reasonably well, while providing a clear color scheme which separates the high values from low values. There are a lot of numbers, and it does get a bit difficult to compare directly between countries.

I decided to organize the data differently, using different axes. I wanted to make a visualization where I could compare the range of debt-to-GDP ratios between 1995 to 2022 from one country to another, making location and value the axes, and choosing box-and-whisker plots to show the range, quartiles, and median of each country (sorting each country by the median value within the time frame). Each gray point in the graph represents one year's debt-to-GDP ratio for a given country - I wanted to make these points background features, so the box-and-whisker plots would pop more. There weren't many options for color with the box and whisker plots in Tableau, so I chose a basic teal color scheme, with darker teal below the median (lower debt-to-GDP ratios) and lighter teal (higher GDP ratios) above the median. 

I think that my visualization did a better job of comparing debt-to-GDP ratio between countries than the heat map, and was able to have a similar effect as the bar chart while using a much larger range of data (the bar chart only looked at one year's figures). There is a bit more knowledge required to read the box-and-whisker plots, but I do feel it's relatively intuitive to understand at least that the represent the range of data points, especially given the title of the graph.
