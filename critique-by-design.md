| [home page](https://aaifeng.github.io/portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design

## MakeoverMonday Visualization: Who do we spend time with across our ifetime?
Original visualiation from Our World in Data: [https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime](https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime)

<iframe src="https://ourworldindata.org/grapher/time-spent-with-relationships-by-age-us?stackMode=absolute%C2%AEion" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>

## Critique

I chose to critique and redesign the visualization from Our World in Data about average time spent per day with or without company for Americans.

My overall observations are that the original data visualization is effective and informative. While it is not necessarily telling a story, it does have all the elements necessary to do so and it is already relatively easy to understand without the viewer spending too much time on it. The simplicity of the line graph with just six categories significantly helps with how easy it is to understand the visualization. The interactive element with the mouse-over statistics also helps with comparing the categories at once at specific points in time. I think the graph works well for its purpose. However, I did not fully read the subtitle and note until well into my visual analysis, and that information would have been helpful in my initial understanding of the visualization. I would try to reduce the wordiness of that information, as well as remove the callout lines for the category names and reduce the number of tick marks on the y-axis to reduce overall clutter.

### Stephen Few Method

The Stephen Few method involves a sliding scale for seven categories:

- Usefulness
- Completeness
- Perceptibility
- Truthfulness
- Intuitiveness
- Aesthetics
- Engagement

I think this method puts more emphasis on audience and the perception of the data's message, as opposed to the Good Charts method, which is centered around the viewer's gut reaction and tailored towards the sketching and prototyping process. I think the Good Charts method is more helpful as a starting point for the creation of a new graph, and the added Stephen Few method can provide more insights on how the intended audience might read and interpret the graph. In this case, I appreciated using the Few method because I needed to think more about the context of the graph than just the graph as a stand alone.

For both perceptibility and intuitiveness, the visualization type, a line graph, is one that is easy to interpret, and this graph only has 6 categories that it is tracking overtime. After reading the subtitle, I do believe that the visualization is complete with all necessary elements. Each axis is labeled, the categories are labeled, and the title and subtitle contain information about the time span of data collected and where it was collected. The note at the bottom also compensates for the lack of a complete day in minutes represented on the y-axis. Hand-in-hand with truthfulness, I think the completeness of the graph compliments how truthful it is in this case. I was left wondering, however, how big the sample size was for the surveys, which I could not find on the graph or in the article. In terms of aesthetics, it is not a particularly beautiful data visualization, but I do think that it is straightforward and relatively easy to interpret. I think what makes it interesting to look at is its engagement factor, because minutes spent per day is something that everyone can relate to, if not for themselves then for someone they know, like aging parents. The diverging lines towards the right side of the graph (older ages) also naturally attracts the viewer's eye.

While I don't think the audience is entirely clear in the article, I do think the visualization provided useful information to whom I think is the target audience. This data is part of an article that was published in November of 2020, so whatever audience is reading the article is one that has been affected by COVID-19 and is hyperconscious of their time. Given that the article is published on a data-focused website, my guess is that this data would then be repackaged by reporters and news outlets to comment on behavior patterns pre-COVID-19 as compared to emerging and potential patterns in these unprecedented times. To that end, I think the visualization is effective for reaching that audience because it is large and complete enough for news outlets to each glean different headlines from it. It seems to have a lot of different potential stories that can be told through visualization.

I would consider reducing the data into age increments (i.e., 15-29, 30-44, etc.) and use a bar graph to better visualize which categories dominate those age ranges. I would also consider only comparing the categories for age 40 and age 65 to show when increased time alone starts versus retirement age.

## Sketching & Prototyping

Just from observing the original visualization, I was immediately intrigued and surprised by the increased time spent alone starting at 40 years of age, which felt rather young to me. I would have thought that increased time alone would spike at the U.S. retirement age, which is 65 years of age. This thought process led to sketch 1 below. I wanted to highlight the line for time spent alone, and I wanted to make a note of the divergence starting at 40, as well as the retirement age at 65. I also modified the title to lean into what I was interested in showing more prominently. I did keep the x and y axis relatively the same, with the exception of removing some of the tick marks to reduce some clutter.The other categories were muted in gray since I thought that their context was interesting but not the focal point, and the decision to reduce the line weight of time spent alone before the 40-year mark was once again to emphasize the change that happens at 40. I was on the fence about changing the line weight, so I decided to keep it in so that I could get feedback on it.

### Sketch 1

![Sketch 1](sketch-1.png)

After finishing sketch 1, I realized that I saw the times spent with varying people as distinct categories, and thought that a stacked bar chart might be interesting. What is different in sketch 2 from sketch 1 is that I am no longer focused on a trend starting at age 40, rather just an overall dominance of average time spent alone per day throughout a lifetime. With the focus on time spent alone, I felt comfortable moving forward with a stacked bar chart if time spent alone was the foundation of the bar, which is the area that is easiest to read and compare. Again, I was less interested in the other categories so I was not as concerned that they would not be as easily comparable. I also grouped some of the categories since the focus is on time spent alone. I refrained from making these completely binary categories (i.e., time spent alone vs time spent in general company) because I think having some of the categories provides important context for viewers to understand what exactly is being compared. "Time spent in general company" or "with other", in my opinion, requires a bit more processing than I would like for this graph.

### Sketch 2

![Sketch 1](sketch-2.png)

In one last effort to think out of the box, I thought size of shape, akin to a tree map, might be an interesting way to display the amount of time spent alone as compared to the other categories. In this case I took four ages that span the data to represent how the categories shift over time. While I like the visual comparison of the circles, I felt that this sketch was not as easy to grasp as the previous sketch.

### Sketch 3

![Sketch 1](sketch-3.png)


## Testing through Interviews
I debated between sketch 1 and sketch 2, ultimately deciding to show both sketches to the people I would interview. I asked two people the following five questions. I presented them first with sketch 1 and then asked their thoughts on sketch 2, and if they had a preference between the two.

- Can you tell me what you think this is?
- Can you describe to me what this is telling you?
- Is there anything you find surprising or confusing?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?

### Interviewee #1: adult, early 60s

### Interviewee #2: adult, late 20s


## Redesign

After hearing the feedback from the people I interviewed, I ended up changing directions and moving forward with the concept for sketch 2. I agreed with the feedback that the categories were more discernable in sktech 2 and that the layout of the visualization helped clarify that the variable being measured is percent of time in a day. I did follow the Watch Me Viz tutorial out of curiosity, however they made few changes to the visualization as they already liked its original form.

<div class='tableauPlaceholder' id='viz1700089348739' style='position: relative'><noscript><a href='#'><img alt='Time Spent Alone Increases with Age for AmericansBased on averages from 2009-2019 survey responses (source: Our World in Data) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ti&#47;TimeSpentbyAge&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TimeSpentbyAge&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ti&#47;TimeSpentbyAge&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1700089348739');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
Ortiz-Ospina, Esteban, Charlie Giattino, and Max Roser. “Time Use.” Our World in Data, November 29, 2023. [https://ourworldindata.org/time-use#how-are-working-hours-measured-and-what-can-we-learn-from-the-data.](https://ourworldindata.org/time-use#how-are-working-hours-measured-and-what-can-we-learn-from-the-data)
