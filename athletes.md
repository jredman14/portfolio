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

Still, I decided to show both of these ideas to potential users for feedback, since some parts of one visualization could be superior or inferior to the other - I could forsee a scenario where feedback on an idea I didn't end up using could still be helpful in producing the final product. So, I found two people, both young adults in their mid 20s, to show these visualizations to.

# User Feedback
