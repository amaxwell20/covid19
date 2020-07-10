## Objective COVID-19 Data by U.S. County
#### By Andrew Maxwell

Parsing through the various news and media sources for localized COVID-19 Data can be very difficult if one does not know where to look. The goal of this site is to provide simple datapoints and figures that the everyday individual can use to understand how the COVID-19 pandemic is affecting their community. This data is current as of 7/10/2020.

#### Objective COVID-19 Measures by County
In the graphic below, we divide cases and deaths into totals (all during the pandemic) and recent (in the past 2 weeks). This division allows you to see the overall impact of the virus on your county as well as the current condition in your county. For reference:
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


#### Modeling the COVID-19 in Crowds of Varying Size
To better understand the gravity of the ongoing pandemic, we translate our per-capita case numbers into a probability of at least 1 person having COVID-19 in crowds of varying sizes. Using a model developed by Georgia Tech and Stanford researchers ([Crowd Modeling](https://covid19risk.biosci.gatech.edu/)), we can estimate the potential for you to encounter someone with the virus in your community. While this model does not describe the potential for transmission (which varies based on adherence to social distancing principles), it does provide community members with an idea of what they may encounter by going to a dinner party, a house party, or a political rally.

We base this model off of reported cases, which undercounts the true number of cases. The CDC estimates the actual number of cases is 10-12x as many as the reported number ([CDC - Actual Cases](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/commercial-lab-surveys.html)). Our model does not account for the undercount. When viewing the probabilities for your selected county, keep in mind the actual probability may be as much as 10x higher. 

<body>
  <style>
    html
  </style>
<div class='tableauPlaceholder' id='viz1594091521664' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Probability&#47;ProbabilityDash&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CommunityCovidTableau_Probability&#47;ProbabilityDash' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CommunityCovidTableau_Probability&#47;ProbabilityDash&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1594091521664');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
  </body>
<p>&nbsp;</p>

#### Data and Methods
While this data is updated frequently, there is significant lag time associated with COVID-19 reporting. A county that appears calm today may see spikes in the coming weeks if proper social distancing is not adhered to ([CDC - Social Distancing](https://www.cdc.gov/coronavirus/2019-ncov/prevent-getting-sick/social-distancing.html)). 

Covid data was sourced from USA Facts daily ([USA Facts Data](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)), compiled using python, and presented in Tableau. Per capita cases and deaths were used to compare the pandemic's impact on each county. Population estimates were collected from the 2018 American Community Survey ([ACS Data](https://www.census.gov/programs-surveys/acs)). 
