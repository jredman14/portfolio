| [Home](https://jredman14.github.io/portfolio) | [Visualizing Debt](govdebt) | [Critique by Design](athletes) | [Final Project 1](finalproposal) | [Final Project 2](finalwireframe) |

# My Final Data Story
> Include a link to your final data story on Shorthand, Esri StoryMaps, etc. here. 

# Changes Made Since Part 2

To start, I uploaded my writing into Shorthand, then embedded my visualizations in the text. I also added a few pictures from Unsplash (no copyright) that depicted places in northern Virginia (I checked the locations listed in the photo descriptions) to add another interesting visual element, and break up the very long stream of line graphs that my story contains. I added a few major design elements too: a choropleth map of Census block housing density in Fairfax, Arlington, and Loudoun Counties (I could not find data for Prince William County), a map showing the growth of impervious surfaces in Los Angeles County, California from 2001 to 2021, and a new section showing a definition of urban sprawl from a quote by [John Rafferty](https://www.britannica.com/explore/savingearth/urban-sprawl). 

I added the choropleth map after my interviews, when one interviewee suggested that housing density could help provide more context to my discussion of sprawl. I found feature classes for 2020 Census blocks in Fairfax, Arlington, and Loudoun Counties, as well as corresponsing housing unit datasets for Fairfax and Arlington (the number of housing units were included with the Loudoun Census Block feature class). After a little geoprocessing, each county Census block feature class (besides Prince William, where I couldn't find the necessary housing data), had a column that included the total number of housing units (including apartments) within each block. Then I symbolized with quantile classifications in Fairfax County and used the same classification intervals for Loudoun and Arlington (so the map had the same classifications across all three counties). 

After the in-class critique, I added the Los Angeles case study, when one of my classmates noted that my presentation lacked the context necessary to make sense of my facts and figures and suggested some other municipality to compare against. LA was an interesting example, since it has been well known for its car culture and sprawl. Finding sources noting its overall improvement made it a no-brainer choice for a case study. To make the impervious surface map, I found an LA County Boundary feature class and used the same raster dataset showing impervious surfaces.

The definition section was based on feedback from an interviewee, saying that I needed to define some of my jargon for the average reader. Even though I did not intend for the audience to be the general public (more on that later), I thought that adding a definition could make the overall design less monotonous and more interesting, and served as a good introduction to the final part of the story. 

I also tweaked some of my narrative, mostly to soften my conclusion a bit - I didn't want to imply that development should only occur in the inner suburbs, I mainly intended to drive the point home that development should be mostly limited to the current impervious footprint. We can't undo previous development, but we can make our current urban footprint more dense, walkable, and connected over time. I expanded my intro section from Part 2 to include my summary from Part 1, which I felt was a more complete overview of the project. 

I also changed the colors of my lines on my line graphs - in Part 2, each individual county line was gray so that the mean/sum line could stand out for each measure. However my interviewees said that it was very difficult to make any meaningful comparison between individual counties when all the lines were gray. I didn't figure out how to make all but one line more transparent, but I was able to give each county a different color while widening the mean/sum line for each graph. This way, readers can compare and contrast the measures for each county, but the overall trend line stood out. 

## The Audience

I thought of this as a presentation to a city council or local government to introduce some of the pressing issues facing the community. I didn't focus so much on making my presentation particularly accessible to everyone, and more focused on speaking to the issues specifically and concisely. I still wanted the presentation to be relatively attractive, and I included pictures of northern Virginia areas to make it more visually appealing. But I was okay with not using a variety of visualization types - the line graphs were a bit repetitive, but I didn't think there was a more clear way to showcase the data. 

I also didn't want to include unnecessary text, and tried to showcase the main takeaway point of each visualization in large heading-style blue text. Since presentations to policymakers can be very crunched for time, even if stakeholders were not able to digest every word, they could still understand the main takeaway points of my analysis.

# Final Thoughts

Overall I think my project was fairly successful, given the time constraints I was working with. I would do more complex analysis (such as automating a process in ArcGIS or using Excel/SAS/R) if I had more time, and I think I would have come up with some interesting conclusions. However, I don't know that I would have come up with an argument that was considerably more useful than my current argument, especially considering my audience might not understand more complex methods of analysis. 
