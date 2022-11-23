# Accidental Drug Overdoses in the United States

## Outline
With the increase in drug overdose deaths, the US Centers for Disease Control and Prevention's Injury Prevention & Control office states that the US is in an "overdose crisis." Because this is such a prominent issue in the United States today, I'm looking at accidental drug overdose statistics. I want to start by exploring where in the United States accidental drug overdoses are most commonly occuring. A quick glance at the data shows that there are some municipalities that have more accidental drug overdoses than other municipalities. Next, I want to look at potential reasons for why accidental drug overdoses are more common in those municipalities. I plan to expand off of the [Center for Disease Control and Prevention's State Unintentional Drug Overdose Reporting System (SUDOR)](https://www.cdc.gov/drugoverdose/fatal/dashboard/index.html) by focusing on one of the states with the highest amount of accidental drug overdoses. I'd like to then look at crime datasets, and census datasets for the county with highest amount of drug overdoses. Finally, I want to explore what can be done to help those areas. 

My story structure will be broken up into "three basic dramatic parts" as told by Scott Berinato in Good Charts

**Setup:** where in the United States is the drug overdose problem the worst?

**Conflict:** what factors influence areas to have bigger issues with drug overdoses? Is there a certain demographic who experiences a higher number of overdoses?

**Resolution:** what can we do to decrease drug overdoses in the United States?

## Sketches

<div class='tableauPlaceholder' id='viz1669176106922' style='position: relative'><noscript><a href='#'><img alt='&lt;Accidental Drug Overdose by State, 2020&gt; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;SU&#47;SUDORSOverdosetreemap&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SUDORSOverdosetreemap&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;SU&#47;SUDORSOverdosetreemap&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669176106922');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

This tree map displays the 29 states that submit reports to the Center for Disease Control and Prevention's State Unintentional Drug Overdose Reporting System (SUDOR). SUDOR's purpose is to "presents comprehensive information on the characteristics and circumstances surrounding drug overdose deaths to inform prevention and response efforts". The data is submitted by states, who pull overdose death statistics from from death certificates, medical examiner/coroner reports, and postmortem toxicology results. 

<div class='tableauPlaceholder' id='viz1669185195398' style='position: relative'><noscript><a href='#'><img alt='Overdoses by Sex in Ohio, 2020 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DemographicsCharts&#47;Sheet5&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DemographicsCharts&#47;Sheet5' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DemographicsCharts&#47;Sheet5&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669185195398');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

This bar chart explores the breakdown of deaths by gender across Ohio. We can see that men more than double the women's statistics. This is valuable because it could give us insight as to what factors increase the liklihood of overdosing, which would influence our resolution plan. 

<div class='tableauPlaceholder' id='viz1669185263375' style='position: relative'><noscript><a href='#'><img alt='Overdoses by Age in Ohio, 2020 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DemographicsCharts&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DemographicsCharts&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DemographicsCharts&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669185263375');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

This bar chart shows the breadown for overdoses in Ohio by age. We can see that majority of overdoses happen to 35-44 year olds. This is valuable because it could give us insight as to what factors increase the liklihood of overdosing, which, similarily to the sex demographics, could influence our resolution plan. 

<div class='tableauPlaceholder' id='viz1669178721475' style='position: relative'><noscript><a href='#'><img alt='&lt;Ohio Drug Overdose by County, 2020&gt; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Oh&#47;OhioCountyDrugOverdose&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OhioCountyDrugOverdose&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Oh&#47;OhioCountyDrugOverdose&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669178721475');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

This treemap explores the counties across Ohio to see if any counties had a higher concentration of overdoses. According to the data, Franklin county had the highest amount of overdoses in 2020. I wanted to make a map on the state, but Tableau did not recognize all of the counties as counties, so it only mapped about a third of the counties. I want to fix this before the final project is due. 


## Data

I will likely add more datasets as I progress through the final project, but I am starting with two datasets.

My first dataset is the [Center for Disease Control and Prevention's State Unintentional Drug Overdose Reporting System (SUDOR)](https://www.cdc.gov/drugoverdose/fatal/dashboard/index.html). I will use the data from this dataset to explore where in the United States accidental drug overdoses are most prominent. A limitation with this dataset is that only 29 states have reported their accidental overdose data to the CDC's SUDOR system. Because of this, we can only compare states that have submitted their data to SUDOR. 

My second dataset is from [Ohio's Department of Health](https://odh.ohio.gov/know-our-programs/violence-injury-prevention-program/media/2020+ohio+drug+overdose+report). Because Ohio has the highest number of drug overdoses in the SUDAR's dataset, I will use this dataset to explore the entire state's statistics. From this data, I will get the county with the highest number of drug overdoses. Getting this information will help me look at potential root causes of why drug overdoses are so prominent in that county. From my visualization above, it is clear that Franklin County has the highest number of drug overdoses for 2020. I am currently researching more about why that could be. 

## Method and Medium

I will be completing the project using free hand sketches, Tableau, Flourish, and Shorthand. I will use free hand sketches to create my wireframes. I will use Tableau and Flourish to create my visualizations. I will use Shorthand to display my completed final project. 

