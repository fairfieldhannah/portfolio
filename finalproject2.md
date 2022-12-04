# Final Project II -- CONTENT WARNING: DRUG OVERDOSE DEATHS

See my github [portfolio](https://fairfieldhannah.github.io/portfolio)

See my [project 1](https://fairfieldhannah.github.io/portfolio/finalproject1.html)

### Wireframes and storyboards

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

The Center for Disease Control and Prevention's National Vital Statistics System [(NVSS)](https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm) counts drug overdose deaths occurring within the 50 states and the District of Columbia. The data is submitted by states, who pull overdose death statistics from death certificates, compile and send reports to the National Center for Health Statistics (NCHS). 

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

Unfortunately, with the publically available datasets, I cannot determine **why** Cabell and Logan counties have the highest reports of drug overdose deaths rates. Although we cannot find the root cause, there are still measures we can take to decrease the death rates in these communities. 

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

### User Research: Protocol
The goal of this research is to explore why drug overdoses are more prevelent in some places, and what we can do to decrease drug overdose deaths. The goal of the below interviews are to gauge audience understanding of the wireframes and storyboard. 

**a.** the target audience I hope to reach with my story is people who live within the communities with the highest drug issues so they can understand the situation in their local area. This may motivate locals to support their local drug overdose prevention organizations, and carry naloxone hydrochloride.  

**b.** I want to get three people from completely different backgrounds and ages so that I can get as different of people to interview as possible. I want each person to be very different because I want them to provide their honest opinions in how the visualization impacts them. If people have the same background, it's likely that the visualization will impact them in similar ways. 

**c.** My interview script is:

**1. What did you gather from this information?**

**2. What stands out to you?**

**3. Is there anything you would change about my delivery?**

**4. Is this information alarming or expected?**

**5. If this information portrayed your local area, how would you react?**



### User Research: Findings

**a.** I interviewed the following three people:
1. Male, 27 Years Old, Accountant
2. Female, 58 Years Old, Emergency Department Nurse/Research Coordinator
3. Male, 26 Years Old, Student

| Question | Person 1 | Person 2 | Person 3 |
| --- | --- |
| `What did you gather from this information?` | I have a better understanding of the overdoses sitution in the US | I saw overdoses in the US | I learned more about overdoses in West Virginia.
| `What stands out to you?` | I'm still stuck by the Narcan. Administering Naloxone hydrochloride has a negative stigma. Some people have pushed back asking 'why save someone who's just going to use again?' | I'm surprised that Missouri's rate isn't higher. I also thought California and Texas would be higher until I realized it's per capita. | I'm not surprised that West Virginia has the highest because I watched a documentary on Netflix about it a couple of years ago, but it's surprising that the states surrounding West Virginia don't have higher rates. I didn't realize how many states have high overdose numbers. 
| `Is there anything you would change about my delivery?` | No, it was all clear. | I would look more into the medical industry. I know when I worked in the SICU we had issues with nurses either using the drugs, or stealing them to sell them. | Even though there weren't a lot in the findings, I liked that you went through your thought process for finding the root cause.  
| `is information alarming or expected?` | It's definitely alarming. I don't think there's a lot of information about this out there. | I'm really surprised that the numbers are so high. I didn't realize these numbers were that high. I don't know anyone who uses so I'm shocked that there are so many overdoses.  | The numbers are alarming, but also not surprising because I've been seeing more about it over the past couple of years. 
| `If this information portrayed your local area, how would you react?` | I'd look for organizations that I could work with or volunteer at to try to decrease overdoses in my area. | If this were happening in my community it would be helpful to know if this is a problem, and what are we doing to help it?  | I would want to know what my local government is doing. 

**b.** The findings of my interview

-The scale of the overdose epidemic was unknown to all of the people I interviewed, even to the one who works in the Emergency Department at a hospital. When there is little awareness over the scale of any issue, it's difficult to garner public support. Without public knowledge and support, it's more difficult to implement meaningful changes. 

 **"If this were happening in my community it would be helpful to know if this is a problem, and what are we doing to help it?"**

-Although naloxone hydrochloride is proven to reverse overdose there is a stigma around using it. The stigma for family/friends of opioid-users is likely to differ from the stigma of opioid users. Opioid users may feel uncomfortable or embarassed telling their family/friends that they want naloxone hydrochloride. Family/friends may avoid bringing up naloxone hydrochloride to avoid offending their opioid-using loved ones.

**"Administering Naloxone hydrochloride has a negative stigma. Some people have pushed back asking 'why save someone who's just going to use again?'"**
 

**c.** Changes I plan on implementing to your visualizations next week to address the issues identified:

I want to look further into the heathcare industry to see if there is a relationship between higher numbers per capita in the healthcare industry and higher numbers of drug overdose deaths per capita. 


### Resources
[Centers for Disease Control and Prevention Overdose Prevention Campaigns](https://www.cdc.gov/drugoverdose/featured-topics/overdose-prevention-campaigns.html)

[Centers for Disease Control and Prevention's National Center For Health Statistics](https://www.cdc.gov/nchs/pressroom/sosmap/drug_poisoning_mortality/drug_poisoning.htm)

[US Census Bureau US Population](https://www.census.gov/quickfacts/fact/map)

[US Census Bureau West Virginia Population](https://www.census.gov/quickfacts/fact/map/WV,CA/POP645220) 

[DataUSA West Virginia Drinking Statistics](https://datausa.io/profile/geo/west-virginia#economy)

[DataUSA West Virginia Office of Drug Control Policy Data Dashboard](https://dhhr.wv.gov/office-of-drug-control-policy/datadashboard/Pages/default.aspx)

[WorkForce West Virginia Unemployment](http://lmi.workforcewv.org/DataRelease/CountyRelease.html)

[Centers for Disease Control and Prevention Naloxone](https://www.cdc.gov/stopoverdose/naloxone/index.html)

[West Virginia Legislative Changes](https://wvbom.wv.gov/LegislativeChangesAffectOpioid.asp)

[National Library of Medicine's National Center for Biotechnology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3005091/)
