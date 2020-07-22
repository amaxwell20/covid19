<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-172377354-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-172377354-1');
</script>

![image](https://user-images.githubusercontent.com/67279800/87460136-5fdbbc80-c5da-11ea-9731-4114f1f8354b.png)

## Objective COVID-19 data by U.S. county
#### By Andrew Maxwell

Parsing through the various news and media sources for localized COVID-19 Data can be very difficult if one does not know where to look. The goal of this site is to provide simple datapoints and figures that the everyday individual can use to understand how the COVID-19 pandemic is affecting their community. We provide a variety of different perspectives on up-to-date Coronavirus data and attempt to create a community-level understanding of this global pandemic. Below you can find:
- How does your county's crisis compare to others in your state and across the country?
- How do the cases in your county translate to real-world risk of coming in contact with the virus?
- How is the virus changing in your community and across the country?

**Jump to:**
- [Objective COVID-19 Measures by County](#objective-covid-19-measures-by-county)
- [Modeling COVID-19 in crowds of varying size](#modeling-covid-19-in-crowds-of-varying-size)
- [Coronavirus cases and deaths curves by county](#displaying-new-coronavirus-cases-over-time-for-all-us-counties)
- [Map of new Coronavirus cases over time](#mapping-new-coronavirus-cases-over-time)
- [Conclusions](#conclusions)

Our data is current as of 7/22/2020.

#### Objective COVID-19 measures by county
In the graphic below, we divide cases and deaths into total cases (all during the pandemic) and recent cases(all in the past 2 weeks). This division allows you to see the overall impact of the virus on your county as well as the current condition in your county. For reference:
- Each row represents a different COVID-19 measure, and each column shows a different perspective on that measure. 
- The first column shows the county's rate per 100k residents. The second and third column rank the county among all counties in the state and the country, respectively. 
- Below each measure, you can see where your county was 1-week ago and 1-month ago. In this way, you can track county performance over time. 

<body>
  <style>
    html
  </style>
 <div class='tableauPlaceholder' id='viz1593479889942' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_v3&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CommunityCovidTableau_v3&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_v3&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1593479889942');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
  </body>
<p>&nbsp;</p>


#### Modeling COVID-19 in crowds of varying size
To better understand the gravity of the ongoing pandemic, we translate our per-capita case numbers into a probability of at least 1 person having COVID-19 in crowds of varying sizes. Using a model developed by Georgia Tech and Stanford researchers ([Crowd Modeling](https://covid19risk.biosci.gatech.edu/)), we can estimate the potential for you to encounter someone with the virus in your community. While this model does not describe the potential for transmission (which varies based on adherence to social distancing principles), it does provide community members with an idea of what they may encounter by going to a dinner with friends, a house party, or a political rally.

We base this model off of reported cases, which undercounts the true number of cases. The CDC estimates the actual number of cases is 10-12x as many as the reported number ([CDC - Actual Cases](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/commercial-lab-surveys.html)). Our model does not account for the undercount. When viewing the probabilities for your selected county, keep in mind the actual probability may be as much as 10x higher. 

<body>
  <style>
    html
  </style>
<div class='tableauPlaceholder' id='viz1594091521664' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Probability&#47;ProbabilityDash&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CommunityCovidTableau_Probability&#47;ProbabilityDash' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Probability&#47;ProbabilityDash&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1594091521664');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
  </body>
<p>&nbsp;</p>


#### Displaying new Coronavirus cases and deaths over time for all US counties
Our next chart allows you to observe the case and death curves for any county or state in the US. Each column represents a day from April 1st until now. To smooth out the chart's noise, we provide a 7-day rolling average of each metric at every level of analysis. 

It is important to note that at the state and county level, there have been some reclassifications of what is considered a positive test result or a COVID death, which can lead to occasional and random peaks in the data. Observing the chart's trends is more important than day-by-day case numbers. At more granular levels, it can be hard to observe trends in deaths because of the variation in coronavirus severity among different groups. 

<body>
  <style>
    html
  </style>
<div class='tableauPlaceholder' id='viz1595438864116' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Curves&#47;CurvesDash&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CommunityCovidTableau_Curves&#47;CurvesDash' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Curves&#47;CurvesDash&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1595438864116');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
    </body>
<p>&nbsp;</p>


#### Mapping new Coronavirus cases over time
In the following map, we change the perspective on the data above. The image below clearly shows the transition COVID-19 has made from predominantly affecting the Northeast (New York, New Jersey, Massachusetts, etc.) to now mostly impacting the Southeast and Southwest. This transition is mostly due to the differing responses to the pandemic in Northern and Southern states. 

The tool below can be used to observe this transition across the country or in one particular state. You can click on any county to see the number of new cases in that county. Brighter colors represent 'hot spots' of new cases while cooler colored areas have less new cases. Some startling views to explore:
- The initial acceleration of cases in New York followed by a prolonged 'cooling off' period. Currently, there are no counties in NY with over 100 new cases per day. 
- The emergence of new cases in the South starting in late May. Population centers such as Miami, Dallas, and Atlanta appear bright red. Miami-Dade county reached over 2000 new cases per day in early July. **Miami's new cases on July 8th were double the number of new cases in the United Kingdom and France, combined.**
- The consistent number of new cases in Southern California. Unlike New York, SoCal case growth has not leveled off, and unlike Texas and Florida, cases have been growing since late march. This region is especially hard hit by COVID-19. 

![image](https://user-images.githubusercontent.com/67279800/87197032-38c67780-c2c8-11ea-9fb9-9a341a22f3b6.png)

<body>
  <style>
    html
  </style>
<div class='tableauPlaceholder' id='viz1595172036596' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Map&#47;Dashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CommunityCovidTableau_Map&#47;Dashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Map&#47;Dashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1595172036596');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
  </body>
<p>&nbsp;</p>

#### Conclusions
The differing responses to the novel Coronavirus in the US have inhibited our country from quelling the virus. While certain states attempted to crush the virus through stay-at-home orders and strict reopening strategies, others likely opened too early and are now facing the consequences. The same scarcity of ICU beds and ventilators that plagued New York in the spring is now afflicting parts of Arizona, Florida, and California. 

The media has made understanding this virus nearly impossible for the average American. Politicizing this virus has cost our country precious lives and exacerbated the current economic downturn. Social distancing and wearing masks are not political subjects. They are simple measures that everyone can and should take to save lives and return our communites to normalcy. We hope this site has armed you with the facts you need to adjust your lives and the lives of those around you. Simply put, beating this virus requires collective agreement in our communities, our states, and across the nation. 

#### Data and methods
While this data is updated frequently, there is significant lag time associated with COVID-19 reporting. A county that appears calm today may see spikes in the coming weeks if proper social distancing is not adhered to ([CDC - Social Distancing](https://www.cdc.gov/coronavirus/2019-ncov/prevent-getting-sick/social-distancing.html)). 

Covid data was sourced from USA Facts daily ([USA Facts Data](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)), compiled using python, and presented in Tableau. Per capita cases and deaths were used to compare the pandemic's impact on each county. Population estimates were collected from the 2018 American Community Survey ([ACS Data](https://www.census.gov/programs-surveys/acs)). 

#### About the author
Andrew Maxwell is a 2020 graduate from UNC with a B.S. in public health from Gillings. Andrew currently works as a research assistant for Cecil G. Sheps Center for Health Services Research. In October 2020, he will start work as an associate at Boston Consulting Group (BCG). All the work here is his own and does not reflect the opinions of any associated organizations. 
