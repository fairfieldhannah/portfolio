# Final Project III -- CONTENT WARNING: DRUG OVERDOSE DEATHS

See my github [portfolio](https://fairfieldhannah.github.io/portfolio)

See my [final project part 1](https://fairfieldhannah.github.io/portfolio/finalproject1.html)

See my [final project part 2](https://fairfieldhannah.github.io/portfolio/finalproject2.html)

See my [Full Shorthand Presentation](https://preview.shorthand.com/62iYcOHEFVMs0YGy)

See my [60 Second Shorthand Presentation]()

### Background

With the increase in drug overdose deaths, the US Centers for Disease Control and Prevention's Injury Prevention & Control office states that the US is in an ["overdose crisis"](https://www.cdc.gov/drugoverdose/featured-topics/overdose-prevention-campaigns.html). Because many drug overdoses involve multiple types of drugs, I'm looking at all drug overdose deaths in 2021. 

#### **Setup** 

Where in the United States is the drug overdose problem the worst?
<div class='tableauPlaceholder' id='viz1669868535912' style='position: relative'><noscript><a href='#'><img alt='Overdose Deaths by State, 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16698668356120&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_16698668356120&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_16698668356120&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669868535912');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
Source: [National Center For Health Statistics](https://www.cdc.gov/nchs/pressroom/sosmap/drug_poisoning_mortality/drug_poisoning.htm)

The Center for Disease Control and Prevention's National Vital Statistics System [(NVSS)](https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm) counts drug overdose deaths occurring within the 50 states and the District of Columbia. The data is submitted by states, who pull overdose death statistics from death certificates, compile and send reports to the National Center for Health Statistics [(NCHS)](https://www.cdc.gov/nchs/pressroom/sosmap/drug_poisoning_mortality/drug_poisoning.htm). 

We can see that West Virginia has the highest number of drug overdoses per 100,000. To better understand why West Viriginia has the highest number of overdoses from states that reported to NCHS, we can see where in West Virginia the overdoses are occuring.

<div class='tableauPlaceholder' id='viz1669776273811' style='position: relative'><noscript><a href='#'><img alt='West Virginia Drug Overdose Deaths by County, 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book7_16697762671020&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book7_16697762671020&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book7_16697762671020&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669776273811');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
Source: [West Virginia Office of Drug Control Policy Data Dashboard](https://dhhr.wv.gov/office-of-drug-control-policy/datadashboard/Pages/default.aspx)

According to the data, Cabell county had the highest overall number of overdose deaths in 2021, but Logan County had the highest number of overdose deaths per 100,000. 

#### **Conflict** 

To explore what factors influence counties to have bigger issues with drug overdoses, first I looked at unemployment rates by county. I used a packed bubbles chart to see if there is a relationship between the overdose deaths per 100,000 and unemployment rates in each county. I didn't notice any significant similarities between counties with high levels of unemployment and high levels of drug overdose deaths. The only county that is both in the top five of deaths per 100,000, and has a high unemployment rate is McDowell county. Because one county is not sufficient evidence to claim unemployment contributes to overdose deaths, I decided to look at additional data to get a better understanding of why one county has a higher overdose death rate than another.
<div class='tableauPlaceholder' id='viz1669834857191' style='position: relative'><noscript><a href='#'><img alt='Drug Overdose Deaths Per 100,000 and Unemployment Rate by County, 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book11_16698348468280&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book11_16698348468280&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book11_16698348468280&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669834857191');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
Sources: [West Virginia Unemployment Data](http://lmi.workforcewv.org/DataRelease/CountyRelease.html) and [West Virginia Office of Drug Control Policy Data Dashboard](https://dhhr.wv.gov/office-of-drug-control-policy/datadashboard/Pages/default.aspx)

This led me to consider that perhaps one of the reasons for a county to have a higher overdose death rate is the jobs that people living in that county are are doing. Maybe if people are doing highly physical jobs then they're more likely to be injured and require a medical solution which would introduce them to addictive drugs that could lead to an overdose. 

First, I looked to what jobs are most common in West Virginia. Of the top 15 jobs, I consider 3 to be highly physical: construction, coal mining, and truck transportation. 
<div class='tableauPlaceholder' id='viz1669833484174' style='position: relative'><noscript><a href='#'><img alt='Top 15 Most Common Industries in West Virginia, 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book9_16698334389830&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book9_16698334389830&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book9_16698334389830&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1669833484174');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
Source: [West Virginia Economy](https://datausa.io/profile/geo/west-virginia#economy)

Then, I looked by regions to see if any of these jobs correlate with the counties with high levels of drug overdose deaths. [West Virginia Workforce](http://lmi.workforcewv.org/Maps/GeographicalAreas.html) splits the state up in 7 workforce development regions. This is the lowest level that I could get data, so I'm using these regions instead of the indvidual county level. Workforce development region 2 has the highest average of overdose deaths. It includes Cabell county, Putname county, Wayne county, Loncoln county, Boone county, Logan county, and Mingo county.

<div class="flourish-embed flourish-chart" data-src="visualisation/12013396">
  <script src="https://public.flourish.studio/resources/embed.js">
  </script>
</div>

This bar chart does not seem to yield any obvious signifigance in comparing the regions percentage of workforce in physically demanding jobs with counties' overdose death rates. 

In my [final project part 2](https://fairfieldhannah.github.io/portfolio/finalproject2.html), I interviewed a nurse to get use feedback. When I told her that there wasn't a strong relationship between counties with high rates of highly physical jobs and high rates of drug overdose deaths, she asked me how many people are employeed in the medical industry. In her experience, nurses and doctors had easy acess to the drugs and typically abused the availability. 

Because of that, I decided to look into board disciplinary actions for nurses and doctors. Because the West Virginia Registered Nurse Board only releases when nurses are suspended and not what they are suspended for, I looked solely at reasons for disciplinary actions for doctors in West Virginia. 

<div class='tableauPlaceholder' id='viz1670115465514' style='position: relative'><noscript><a href='#'><img alt='West Virginia Board of Medicine Disciplinary Actions, 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book13_16701153397020&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book13_16701153397020&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book13_16701153397020&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1670115465514');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
Source: [West Virginia Board of Medicine](https://wvbom.wv.gov/public/board-actions.asp)

Of the 18 total disciplinary actions, excluding issues involving administrative fees and educational requirements, brought to the board in 2021, 7 of them were because of issues with controlled substances. Almost 40% of disciplinary actions for West Virginia's doctors in 2021 involved controlled substances. In 2018, the United States House Energy and Commerce Committee completed an [investigation](https://republicans-energycommerce.house.gov/opioids-pilldumping/) on 'pill dumping' into West Virginia. Through this investigation, they found fault with doctors, pharmacies, distribution companies, and the Drug Enforcement Agency for the pill dumping problem in West Virginia. Pill dumping is [defined](https://www.cbsnews.com/news/whats-a-pill-mill/) as "a doctor, clinic or pharmacy that is prescribing or dispensing powerful narcotics inappropriately or for non-medical reasons". Consider Mount Gay-Shamrock in Logan county with a population of 1,430. 17,000,000 opioids were distributed there over 10 years to 1 [pharmacy](https://republicans-energycommerce.house.gov/opioids-pilldumping/). That's 11,888 pills per resident. If you were to line all of those pills up in a row, it would stretch 264 miles long. That's further than the distance from Pittsburgh to Washington DC. 


#### **Resolution** 

What can we do to decrease drug overdoses in West Virginia?
West Virginia attempted to decrease drug overdose deaths when the state enacted the [Senate Bill 273 -- The Opioid Reduction Act](https://wvbom.wv.gov/LegislativeChangesAffectOpioid.asp)  in 2018, aimed at reducing opioid prescriptions. Unfortunately, as we can see below, the number of opioid overdose deaths per 100,000 dipped slightly in 2019, before jumping in 2020, and again in 2021. 

<div class="flourish-embed flourish-chart" data-src="visualisation/12013640">
  <script src="https://public.flourish.studio/resources/embed.js">
  </script>
</div>

If legislation regarding the number of opioid prescriptions cannot better the situation, what can?

Naloxone hydrochloride (commonly referred to as the brand Narcan) is known to reverse the effects of a drug overdose. A [study in San Francisco](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3005091/) found that when naloxone hydrochrolide is administered, 89% of overdoses are reversed. 

<div class="infogram-embed" data-id="9546f619-5bd4-4884-99bc-5b8ae1c8ff3f" data-type="interactive" data-title="Pictoral Chart"></div><script>!function(e,i,n,s){var t="InfogramEmbeds",d=e.getElementsByTagName("script")[0];if(window[t]&&window[t].initialized)window[t].process&&window[t].process();else if(!e.getElementById(n)){var o=e.createElement("script");o.async=1,o.id=n,o.src="https://e.infogram.com/js/dist/embed-loader-min.js",d.parentNode.insertBefore(o,d)}}(document,0,"infogram-async");</script><div style="padding:8px 0;font-family:Arial!important;font-size:13px!important;line-height:15px!important;text-align:center;border-top:1px solid #dadada;margin:0 30px"><a href="https://infogram.com/9546f619-5bd4-4884-99bc-5b8ae1c8ff3f" style="color:#989898!important;text-decoration:none!important;" target="_blank">Pictoral Chart</a><br><a href="https://infogram.com" style="color:#989898!important;text-decoration:none!important;" target="_blank" rel="nofollow">Infogram</a></div>


Increasing availability and education in administration could decrease the number of drug overdose deaths. Although expanding naloxone hydrochloride availability and education in adminstration would not treat the underlying problem, it would decrease overall drug overdose deaths. In 40% of overdoses, there is a bystander at the [scene](https://www.cdc.gov/stopoverdose/naloxone/index.html). If these bystanders were able to administer Naloxone hydrochloride, the overdose deaths more than likely could have been prevented.

A significant way to prevent overdose deaths is by taking care of yourself. Don't accept an opioid prescription unless you believe it is absolutely necessary. If you need an opioid prescription, do not accept it without access to Naloxone. Another important way to prevent overdose deaths is by supporting your friends and family. You can do this by becoming trained and educated on administering naloxone hydrochloride. Pennsylvania residents can order free naloxone hydrochloride [here](https://nextdistro.org/pachoice). **After following a short training video and quiz, naloxone hydrochloride is delivered to your mailbox for free.** 


### Summary of Changes After Completion of Part II
The audience for my final data story is local community members for communities impacted by the opioid overdose. After seeing the failures at levels with doctors, pharmacies, distributors, and DEA, it's really important that local communities understand how to protect themselves against a drug overdose. Be cautious when doctors prescribe you with opioids, and if you do have to take them then make sure your friends and family are trained and equipped with naloxone hydrochloride. 

The biggest adjustment from my project 2 to project 3 stemmed from my interviewee who is a nurse. She recommended that I looked into the medical industry, specifically at doctors and nurses. This opened to door to pill mills, which then lead me to the House Committee investigation looking specifically at West Virginia. I wanted to use a dark design on my shorthand page because we are discussing death and death is a dark topic.  

### Resources
[Centers for Disease Control and Prevention Naloxone](https://www.cdc.gov/stopoverdose/naloxone/index.html)

[Centers for Disease Control and Prevention Overdose Prevention Campaigns](https://www.cdc.gov/drugoverdose/featured-topics/overdose-prevention-campaigns.html)

[Centers for Disease Control and Prevention's National Center For Health Statistics](https://www.cdc.gov/nchs/pressroom/sosmap/drug_poisoning_mortality/drug_poisoning.htm)

[DataUSA West Virginia Drinking Statistics](https://datausa.io/profile/geo/west-virginia#economy)

[DataUSA West Virginia Office of Drug Control Policy Data Dashboard](https://dhhr.wv.gov/office-of-drug-control-policy/datadashboard/Pages/default.aspx)

Lauren Enteen, Joanna Bauer, Rachel McLean, Eliza Wheeler, Emalie Huriaux, Alex H. Kral, and Joshua D. Bamberger. [Overdose Prevention and Naloxone Prescription for Opioid Users in San Fransisco.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3005091/).  October 22, 2010. 

Malbran, Pia. What's a Pill Mill? [CBSNews.](https://www.cbsnews.com/news/whats-a-pill-mill/). May 31, 2007.

[National Library of Medicine's National Center for Biotechnology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3005091/)

[US Census Bureau US Population](https://www.census.gov/quickfacts/fact/map)

[US Census Bureau West Virginia Population](https://www.census.gov/quickfacts/fact/map/WV,CA/POP645220) 

[WorkForce West Virginia Unemployment](http://lmi.workforcewv.org/DataRelease/CountyRelease.html)

[West Virginia Legislative Changes](https://wvbom.wv.gov/LegislativeChangesAffectOpioid.asp)
