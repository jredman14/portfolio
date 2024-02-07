# Critique by Design with Tableau (Makeover Monday)

For this exercise, I chose to critique a data visualization from Forbes that appeared on [Makeover Monday](https://makeovermonday.co.uk/) earlier this year. The vizualization showed the [50 highest paid athletes in the world](https://www.forbes.com/lists/athletes/?sh=6cc2c3a95b7e). The visualization was basically just a grid, with rows for each athlete and columns for their sport, total pay, on-field pay (like salary and winnings), and off-field pay (like payments from endorsement deals). There was no color coding or graphical element to the design, only numbers representing each athlete's compensation. I picked this visualization because I thought there was a lot to improve on, and I'm a big sports fan that also pays attention a lot to the business-side (salary caps, collective bargaining agreements, TV deals, and the like) of various leagues and associations.  

Immediately, I wanted to change the format from a grid to a bar graph so there would be a more intuitive visual comparison between the athletes' pay. In the brainstorming process, I also thought it would be interesting to put a spotlight on the differences between on- and off-field pay, since there are some interesting narratives you could draw from that. What does it mean to be an athlete with a huge salary with few endoresement deals? There are a lot of different answers to that question, depending on the circumstance, and I thought that focusing more attention on that aspect of the dataset could make the visualization more thought provoking. 

On the flip side, retired athletes were also an interesting case, since their income came almost exclusively from off-field earnings. Roger Federer, Serena Williams, and Tom Brady making the cut was actually the hook of the article, so it seemed like dedicating some focus in the chart to that case seemed reasonable. Again, the on-field/off-field pay was a metric I felt I could use to highlight this, so I went ahead and began to create some initial visualizations with that in mind.

# Competing Bar Graphs

<div class='tableauPlaceholder' id='viz1707265892124' style='position: relative'><noscript><a href='#'><img alt='Highest Paid Athletes ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Ideas3-4_jredman&#47;Idea1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Ideas3-4_jredman&#47;Idea1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Ideas3-4_jredman&#47;Idea1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707265892124');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This was the first solution I came up with. Overall, I thought it had good bones - there was a clear visual comparison between each athlete's total compensation and the bars were color coded to show the proportion of each athletes income that they earned on and off the field. However, comparing the off-field salary between athletes was difficult, since the bars did not all start from zero. I decided to come up with a second solution to try and solve this issue.

<div class='tableauPlaceholder' id='viz1707266775580' style='position: relative'><noscript><a href='#'><img alt='Highest Paid Athletes ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Ideas3-4_jredman&#47;Idea2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Ideas3-4_jredman&#47;Idea2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Ideas3-4_jredman&#47;Idea2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707266775580');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

I don't know that this graphic was all that successful. It was much easier to compare between catagories, though I think the overall simplicity and intuitiveness of the first graph was lost - it's more difficult to ascertain the total compensation of each athlete (visually, at least). The athletes are still ordered from highest to lowest (relatively speaking) earners, but the graph still feels a bit haphazard.

Still, I decided to show both of these ideas to potential users for feedback, since some parts of one visualization could be superior or inferior to the other - I could forsee a scenario where feedback on an idea I didn't end up using could still be helpful in producing the final product. So, I found two people, both young adults (non-students) in their mid 20s, to show these visualizations to.

# User Feedback

I asked the following questions to each person willing to give feedback:

1. What are your first impressions of each graph?
2. What are the first things you are drawn to?
3. Is there anything that's unclear?
4. Do you think this is comprehensible for a layperson?
5. Would you add/remove/alter any of the features of the visualization?

I thought it was particularly important to gauge how clear the visualization was for an average viewer, since the original visualization (having appeared in Forbes, a very highly-red publication) was probably geared toward the masses. I wanted to make sure the graph was not too complicated, while bringing more to the table visually. 

Both people preferred the first solution to the second. 

Both Person 1 and Person 2 thought that the first graph was much clearer in showing who was the highest paid, with Person 1 adding that the comparison between on- and off-field pay was still possible. Person 2 agreed that the first graph was reasonably clear to a layperson. Both agreed that the second graph's lack of a clear trend was confusing, and that while there was a more direct comparison between the on- and off-field salaries, the answer to the central question of "Who makes the most money?" was made much more unclear by the second graph. Person 2 also liked that the first graph was more "condensed" compared to the second graph, which was more spread out (with two bars per athlete). 

In terms of specific changes they suggested, Person 1 said that the title "Highest Paid Athletes" was clear, but the visualization might benefit from something more "catchy" and something that could "pose a question/story." The title was something of a placeholder already, but I agreed that I could take a more interesting angle for the final product. Person 2 had a difficult time with some fo the fonts, and recommended some use of bolder text to improve readability. 

Feeling fairly comfortable that the first option was my best bet (with a few alterations), I attended the in-person critique session and had another student look at my graph. The student immediately said that the color scheme needed work (using two colors was too much and the colors themselves were a bit too bright) and that I should get rid of the vertical lines marking certain dollar values, since they made the graph look too busy. I also showed the student the second graph and they agreed with most of the points above, and preferred the first graph. 

When I looked at the other student's various ideas for their visualization, I really liked the tree chart they made for their dataset, so we thought it would be interesting to see if a tree chart worked well for my data. Turns out, it didn't work well at all. You can see below:

<div class='tableauPlaceholder' id='viz1707269754054' style='position: relative'><noscript><a href='#'><img alt='Highest Paid Athletes ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Ideas3-4_jredman&#47;Idea3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Ideas3-4_jredman&#47;Idea3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Id&#47;Ideas3-4_jredman&#47;Idea3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707269754054');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

I didn't exactly put much effort into improving the appearance, so this one is by far the most drafty of the prototypes, but it's clear ths data isn't a great fit for this type of chart. The yearly salaries aren't different enough for there to be a clear contrast between the size of each box - it was the most difficult graph I made in terms of making comparisons. And the contrast between on- and off-field pay was completely lost here. This was a fun idea, but in practice it would have been a poor choice.

After incorporating the more superficial changes that other suggested (removing lines from the graph, making use of bold type, etc.), I thought about how some of the other pieces of feedback fit together. The colors being too busy was a difficult problem to solve - I wanted to achieve real contrast between the on-field and off-field sections of each bar without one fading into the background. However, the more I thought about it, maybe I could make my focus be a bit less broad. I was very interested in the retired-players phenomenon, and how off-field pay could be so significant that they could make more than active players. With the feedback about wanting the title to be more "story" oriented, I decided to make that the focus of my graphical narrative. I decided to make the on-field pay gray, while making the off-field pay a neutral dark blue (which stands out without being too bright and flashy). 

I also adjusted the title and subtitle to fit this narrative, while also making them more descriptive and interesting. I also decided to add two notes to the graph, talking about Federer, Williams, and Brady being on the list as retired athletes, directing more focus to them. Overall, I think the revised visualization does a good job portraying the data, while telling an interesting story drawn from the dataset.

# Final Visualization

<div class='tableauPlaceholder' id='viz1707270965757' style='position: relative'><noscript><a href='#'><img alt='Retired Athletes Among Highest PaidOff-the field earnings for Roger Federer, others, rival total compensation of some active players ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-4_jredman&#47;FinalVisualization&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment3-4_jredman&#47;FinalVisualization' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-4_jredman&#47;FinalVisualization&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707270965757');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
