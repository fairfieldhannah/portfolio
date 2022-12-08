# Assignment 3 & 4: Critique by Design

See my github [portfolio](https://fairfieldhannah.github.io/portfolio)

## OVERALL PROCESS

### STEP ONE
Finding a data visualization that needed to be corrected, and also had publicly available data to remake the visualization was difficult. I was looking for a data visualization related to the Department of Defense spending budget but, when I couldn’t find a visualization other than a small table, I decided to find another topic. I searched for crime articles on Google News and came across the article with the data visualization that I used. It was originally in a news story published in the STL Post-Dispatch. The story, “How much crime is in St. Louis? FBI gets numbers wrong after city fell behind on reporting.” Is written by Josh Renaud and was published on November 8, 2022. In short, the story was about the FBI estimating crime statistics for 2021 because thousands of agencies did not transition to the newer NIBRS reporting system, and the FBI discontinued the SRS reporting system. With the midterm elections happening, it was important to the STL Post-Dispatch to publish an article that the crime statistics being used for political motives was not as accurate as the general population likely thought it to be. 


<img width="1391" alt="originalVis" src="https://user-images.githubusercontent.com/116619734/201561549-ba56098e-5f06-4d93-8326-3df02784064c.png">


[Original Visualization Found Here](https://www.stltoday.com/news/local/crime-and-courts/how-much-crime-is-in-st-louis-fbi-gets-numbers-wrong-after-city-fell-behind/article_aae53e3c-5604-56d3-b839-cec0f7cc239d.html)


### STEP TWO
To critique the visualization I followed Stephen Few's Data Visualization Effectiveness Profile. I found the original visualization to be mostly useful, complete, and intuitive but lacking in perceptibility, truthfulness, and engagement. It lacked perceptibility because the stacked bar charts made it difficult to compare the quantity of agencies using the old SRS system. It also didn’t have axis labels so it was not incredibly clear and obvious what the audience is looking at. I found the original visualization to be lacking in truthfulness because it is purely comparing SRS reports to NIBRS reports. We don’t know if there are other reports being made, or if the agency is reporting at all. After reading the article further, we learn that thousands of agencies are not reporting at all, however, we do not get that from the visualization. The combined lack of perceptibility and truthfulness make it hard for the audience to engage. Few’s Data Visualization Effectiveness Profile model helped me see that to better this visualization I should focus on increasing perceptibility and truthfulness, which will increase engagement. To better the original visualization, I decided to wireframe an unstacked bar chart that focuses on a few years to decrease clutter. I compared agencies submitting NIBRS reports, agencies submitting SRS reports, and the total number of crime reporting agencies to try to increase truthfulness. 

### STEP THREE
As stated above, Stephen Few’s Data Visualization Effectiveness Profile guided my corrections and my initial wireframe. To better the original visualization, I decided to wireframe an unstacked bar chart that focuses on a few years to decrease clutter. I compared agencies submitting NIBRS reports, agencies submitting SRS reports, and, to increase truthfulness, I included the total number of crime reporting agencies. I also added axis labels so the audience has a clearer idea of what the visualization is depicting. 

<img width="468" alt="wireframe" src="https://user-images.githubusercontent.com/116619734/201560879-f073ef5d-22a6-41ab-a36a-9faca400d0ef.png">

 
### STEP FOUR
To test the solution, I interviewed two different people for their initial impressions of my wireframe (pictured above). The first person that I interviewed was a 27-year-old male. The second person that I interviewed was a 26-year-old male. I interviewed them seperately so their answers could not influence the others, but wrote them down together below for simplicity sake. The script I used and their responses are below.

----------start of survey and responses------------

*Can you tell me what you think this is?*

The transition from SRS Reporting System to NIBRS Reporting System starting in 1991 showing every 10 years. (male, 27)

It looks like they switched systems to report crimes and the bar graphs talk about which systems they submitted to initially and then the total numbers, so the red and the blue and equal to the green. (male, 26)

*Can you describe to me what this is telling you?*

It would appear that there was a gap between the NIBRS count and the total count. Where are those crimes coming in? Even in 1991, it almost equals green. Where are the third of the crimes? (male, 27)

It’s telling me why there are problems with submitting to two different agencies and it messes with the overall numbers. (male, 26)

*What specific value does this visualization bring?*

It shows the change over time, so it’s obvious that they’ve transitioned. (male, 27)

It brings value but it can be clearer. (male, 26)

*Is there anything you find surprising or confusing?*

In 30 years it has taken agencies this long to switch to the NIBRS system? Also, why don’t the blue and red add up to the green? (male, 27)

Not really. It took a minute to read through the text but I understood the gist of it. (male, 26)

*Who do you think is the intended audience for this?*

FBI leadership to show that agencies are not reporting to them. (male, 27)

The organization that dictates which system they use. (male, 26)

*Is there anything you would change or do differently?*

Add a column for the number of agencies who did not report. (male, 27)

I would change the wording. It’s too wordy, and can be simplified. (male, 26)

----------end of survey and responses------------

Based on the feedback from the people I interviewed, I decided to take out the column for total number of agencies and put in a column for total number of agencies that failed to report. This gives the audience a better visualization for how many agencies used the NIBRS reporting system when the SRS reporting system was discontinued, versus how many agencies simply did not report. I also changed the title and subtitle so it was not as wordy, and more direct. Lastly, I corrected the axis labels. I incorrectly labeled the y axis for “crimes” instead of “agencies”. 

### STEP FIVE
With my original corrections from Stephen Few’s framework, and the feedback from my interviewees, I used Flourish to redesign my final solution. This redesigned data visualization shows the number of crime reporting agencies that used the older SRS reporting system, the number of crime reporting agencies that used the newer NIBRS reporting system, and the number of agencies that failed to report to the FBI. I selected this bar chart because it’s easier to compare year to year the changes between each variable. It’s also telling more of the whole picture than the original visualization with the included numbers for agencies that failed to report. I attempted to show this aspect specifically differently. The article’s title, “How much crime is in St. Louis? FBI gets numbers wrong after city fell behind on reporting.”, puts a lot of the blame on the FBI when thousands of agencies failed to report to the FBI. It may be the FBI’s fault for sunsetting the old SRS reporting system when thousands of agencies were still using that instead of the newer NIBRS reporting system, but that is not the story that the original visualization is telling. I used color brewer to ensure my colors are colorblind save.

<iframe src='https://flo.uri.sh/visualisation/11802092/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/11802092/?utm_source=embed&utm_campaign=visualisation/11802092' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>
 
