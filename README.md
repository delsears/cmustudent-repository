# cmustudent-repository
# **Delaney Sears Portfolio**
My portfolio page for Telling Stories with Data, Spring 2022

*Quick Links*:

[Assignment: Govt Data](https://delsears.github.io/cmustudent-repository/#assignment-visualizing-govenrment-data)

[Assignment: Design and Redesign](https://delsears.github.io/cmustudent-repository/#assignment-2)

### *About Me*
Hi! I'm Delaney (she/her). 

I am a first-year Entertainment Industry Management student interested in market research, content development, and ultimately producing to tell stories that don't usually get to be told. Data is an important part of this - we need to understand data to know what content will work, what audiences want to see, and what will ultimately be successful in an increasingly digital entertainment world. I had a computer science minor in college, leading me to use a data-driven approach to content development.

### *What I Hope to Learn*
As someone who's been a graphic designer, I've always drawn things by hand - I really would love to learn how to create visualizations using data and Excel and other software to not have to draw so many graphs by hand on my iPad. I've been spending my entire education finding the overlap and balance between art and science, and more specifically media and progrmaming. This is just another very important step on that path! 

### Portfolio 
Here is all of the work I created in the Spring of 2022! 
https://delsears.github.io/cmustudent-repository/ 

### Assignment: Visualizing Govenrment Data
The following visualizations are sourced from OECD, discussing government debt as a percentage of the respective country's GDP. 

##### *Government Debt as % of GDP - Bar Chart* 

<iframe src="https://data.oecd.org/chart/6BjA" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6BjA" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

##### *Government Debt as % of GDP - Stacked Line Chart*
This visualization takes the Government Debt as percentage of GDP ratio of 45 countries around the world, spanning from 1995 to 2019. There are also graphs showing the average of these ratios at the bottom of the collection. 

<div class="flourish-embed flourish-chart" data-src="visualisation/8563088"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

##### *Government Debt as % of GDP - Treemap!*
This visualization is very different from the previous two; it presents the data as more parts of a whole. Each country, with data from 1995 to 2019, is sized by their *count* - in this case, the overall sum of their Debt-to-GDP Ratio. Within each block of a country, the user can mouse over individual blocks of years to see the ratio of that year - the years are also sized by the size of the ratio. 

The benefits of this visualization, and why I chose the treemap for this third visualization of the same data, is that it puts the overall performance over 25 years of each country in comparison with each other. By simply looking at this graph, you can see that Japan has the overall greater Debt-to-GDP ratio. It's more about comparision as parts of a whole than the individual numbers (like the bar graph) or change over time (the stacked line charts). Each graph will have a different outcome for a different audience - this third one, the treemap, would be best for an audience trying to determine overall country performance in terms of debt over the past 25 years as a whole. The treemap almost visualizes total government debt of the world as one big piece, and each country takes a slice of that piece determined by the ratio of their debt to their GDP. It tells a whole story in just one look. 

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/8563257"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### **Assignment 2**

As someone passionate about the environment, and subsequently decreasing meat consumption, I found two separate graphs depicting both the Global Meat Consumption of various meat types frmo 1990 to 2020 and the Global Meat Substitute Consumption (and projection) from 2013 to 2026. Screenshots of the files are below. 

<img width="720" alt="Meat Consumption" src="https://user-images.githubusercontent.com/97906084/152657276-f2678c91-248d-4785-853a-8606de6ec387.png">
SOURCE: OECD, FAO
[Original Site](https://www.statista.com/statistics/274522/global-per-capita-consumption-of-meat/) 
<img width="728" alt="Substitute Consumption" src="https://user-images.githubusercontent.com/97906084/152657285-714e4247-e473-4a84-ba91-7fb4d560d3db.png">
SOURCE: Statista
[Original Site](https://www.statista.com/forecasts/1276467/worldwide-meat-substitute-consumption)

Not only did I want to combine these visualizations into one graph, but I did not enjoy how the Global Meat Consumption graph visualized each type's growth. It was confusing, hard to read, and didn't tell a clear story. 

#### **My Redesigns**
I created my sketches *BEFORE* translating the two data sets into the same set of the same scale - this is important information when it comes to my process. I wanted to put both sets of data on the same graph, either showing change over time - and thus the steady recent growth of meat substitutes - or the proportion of the market each holds. Because I did not know conversion yet from kilograms (original units of the Meat Substitute data) to tons (original units of Global Meat Consumption data), my sketches ended up not looking like my final product. Even then, they helped me figure out which graph type might be best for this project. 

![Untitled_Artwork 86](https://user-images.githubusercontent.com/97906084/152843362-9cffa6a9-6187-4b82-83aa-b7c85acfa8a2.jpg)

With both the line chart and the pie chart, I anticipated the meat substitutes to be...well, a much more significant aspect. When I created my new data set and converted the data to the same units, however, the drafts started looking a bit grim. 

It was at this point that my story changed - instead of showing the impressive growth of meat substitues that I anticipated, the story the data was telling was now "If you thought meatless eating was a huge new trend, it's actually not making a dent."

The feedback from my interviews basically confirmed that: that the meat substitute data was incredibly small, but that it still told a story. Since this was now my focus, I changed the meat substitute color to green and the rest to neutrals and pinks - the green will catch your eye, even if it's a tiny part of the graph. I ended up finishing this assignment with two graphs - they tell similar stories, but in different ways. 

The line graph shows the change over time - the meat substitute data only starts in 2013 and then projects to 2026, so thanks to user feedback I added a line demarcating the present day (in this case, 2020, as that is when the meat data ends). There was an alternative version of this graph that used logarithmic units - it showed a more impressive change over time for the meat substitutes, but also seemed a bit misleading, so I stuck with the original raw units. 

The circle chart shows not the change or growth, but the relative size of the market of each meat in any given year. On the right, the user can select their year - it'll default to 2020, the most recent, but clicking through different years can show gradual changes, if even in a less obvious way than the line graph. 

One graph shows growth - and is still interesting regardless of how small the meat substitute data is. The other shows these meat types in comparison to each other, showing the behemoth that is animal meat consumption versus what people assume to be a "booming" industry of meat substitutes. 

**Line Graph**
<div class='tableauPlaceholder' id='viz1644254638650' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MeatSubstitutesThroughtheYearsFINAL&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1644254638650');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement); 
</script>


**Circle Chart**
<div class='tableauPlaceholder' id='viz1644254687320' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MeatSubstitutesThroughtheYears&#47;Sheet13' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1644254687320');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
