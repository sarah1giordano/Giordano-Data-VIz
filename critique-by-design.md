| [home page](https://sarah1giordano.github.io/Giordano-Data-Viz/)| [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |
 
# Critiquing and Redesigning a Visual on the Human Development Index over Time

## Step one: the visualization

I chose the below visual on the Human Development Index (HDI) over time for a few reasons. First, I didn't think the visual was bad - I understood what they were trying to convey, and felt that there were opportunities to convey this message in different ways more effectively. Second, the visual intrigued me - it left some questions that it did not answer, such as why they included the global financial crisis as a region on the line graph when you can't see a change in HDI. It made me want to dig into the data more to understand the trends and piqued my curiousity. Third, the data source included all the information I thought was necessary to redesign the visual and stay true to the intent of the original message. 

<img src="HDI Original.png" width="600"/>
[Source]([https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2022&oecdcontrol-0b0bb95ebb-var1=OECD_REP%7CCAN%7CCHL%7CCOL%7CCRI%7CMEX%7CUSA%7CGBR%7CTUR%7CCHE%7CSWE%7CESP%7CSVN%7CSVK%7CPRT%7CPOL%7CNOR%7CNZL%7CNLD%7CLUX%7CLTU%7CLVA%7CKOR%7CJPN%7CITA%7CISR%7CIRL%7CISL%7CHUN%7CGRC%7CDEU%7CFRA%7CFIN%7CEST%7CDNK%7CCZE%7CBEL%7CAUT%7CAUS](https://www.bbc.com/news/world-62824357.amp))

## Step two: the critique
**What worked well:** One of the first messages I took away from the visualization was that, overall, HDI declined in 2020 compared to where it was projected. I felt like this was clearly communicated based on the different colors of the projected and actual lines and the dashed line for projected HDI. This worked well in the visual, and led me to score the visual highly for perceptibility. It was also intuitive to read; they did not try to use a fancy visual to convey trend over time when a line graph, which many of us can quickly read, would do. The design choice of using a dashed line for projected HDI was also intuitive. 

The lack of gridlines, simple color scheme, and minimal detail also worked well aesthetically, allowing me to quickly understand the visual. I do wish that aesthetically, it was a little more beautiful (perhaps with a better typeface), but overall, this was neither ugly nor beautiful and the aesthetic choices increase understandability instead of detract from it. 

**What did not work as well:** The bars for the global financial crisis and the Covid 19 pandemic also stood out to me. This did not work quite as well; while it was clear that they wanted to convey that these time points were important in terms of Global Human Development, only the Covid 19 pandemic was associated with a clear change in HDI. I was left wondering why they bothered to highlight the global financial crisis. Was it to convey that HDI overall didn't decrease during the crisis, contrary to expectations? Or was it included because for some countries, this did have a negative impact (and we just cannot see this because the data are aggregated?)  This lack of clarity is part of the reason why I scored the usefulness and completeness of the visualization as only moderate (5). 

In general, I wished there had been more information to support a deeper level of understanding. There was very minimal information included in the visual compared to the article, which noted that "nine out of ten countries have slid backwards." It would have been helpful to see the disparities and differences in the line graph, without so much information that it becomes overwhelming. Greater context for the visual would have been helpful as well: I assumed that this "actual" line was a global average for HDI, but this isn't confirmed in the visual. If it is in fact an average, they could have noted this in the title. If it is an average, context across the line for the outward bounds (the highest and lowest HDI at each time point) could have helped give context for the range between different countries as well, without needing to specify each country on the visual. These thoughts contributed to my score of 5 for both usefulness and completeness. It also contributed to my score of 4 for engagement; as a reader, I wanted to engage more with the visual, but it did not include enough information for me to engage with it past the first two ideas. I found myself curious and searching for more understanding without avenues to do so. 

It also stood out to me that the y axis jumps from 0 to .5. While they do mark this jump, in general, I think the visual would be more truthful if it is shown fully at scale. To improve the truthfulness, I would have changed the y axis to start at 0 and increase steadily at .1 or .2 ticks. 

**Audience efficacy:** I think the audience is a general audience not necessarily well versed in the UN's Human Development Index but interested in global issues. The audience is also likely mostly readers from developed countries, primarily from the UK, given the source (BBC News). This article was more of a summary of a UN report than new analysis and does not include a call to action, so I would argue that this is intended to inform people first so they can potentially be moved to action at a later date. 

I do think this visual could be easily understood by this audience, but I'm not sure that it is effective in answering a question of "so what" for them or keeping their attention. Particularly since it was published by the BBC, maybe including a separate line showing the global average compared to the UK would have helped readers situate themselves more within the visual and connect with it. One thing that really resonated with me from the "Data is Personal" article is how much more effective visuals are when they connect to something in the reader's life, whether that be a focus on the place they live or an issue that is important to them. There aren't any details in this visual that I think a reader - from any audience - could form an emotional connection with, given how general it is. 

**My recommendations for change:** I identified a few different priorities for change based on this critique. 

1. Change the type of visualization because the simple line graph does not convey enough information or detail on changes in HDI globally. I would try something like the gapminder demo or a map (which I test in the next section), to allow me to break out this data by country (or at the very least by region).
   
2. Include a description of what HDI is as a caption for the visual. While a lot of us can intuit what HDI might mean, I think the visual would benefit from a caption with the exact definition and measures that go into hit. HDI includes measures on education, health, and standards of living in each country. These measures include: life expectancy at birth, mean years of schooling of adults aged 25 years and older, expected years of schooling for children, and gross national income per capita. (UNDP, 2024).

3. Make the scale clearer - no jump in the axis! If I stick with something scaled like the gapminder visual, even if HDI values are in a range of .5 or higher, I'd recommend keeping the scale such that each increment is the same size, and there are no jumps.

4. Since HDI has generally increased globally, I recommend switching to percent change in HDI, so we can see differences in slope (this would maybe solve my questions about the global financial crisis earlier - maybe HDI didn't decrease globally, but growth did slow down, which is hard to see from just the HDI value itself.) This would still give us information on whether HDI is improving or not (e.g., the direction it is heading) but would show a lot more nuance in how quickly it is changing. Or, if breaking the data out by country, it might be enough information to just note whether the country-level change was positive, negative, or neutral. I'll test out both of these ideas as I move forward. 

**Final thoughts on this method of critique:** I did like this method of evaluating the data visualization! It forced me to think through more aspects of a successful visual than I likely would have otherwise, although I wish that alongside each ranking it would have explicitly asked for one thing that I think could be done to improve this score. I do think it also helped me see how one design choice can impact multiple elements of a visual, sometimes both positively and negatively - for example, including only one line on the graph for HDI overall helped with initial perceptibility and intuitiveness, but detracted from usefulness and completeness, in my opinion. 

## Step three: Sketch a solution

In keeping with my critique and recommendations, I first tried out and tested the following sketch (taking inspiration from Hans Rosling's gapminder visualization, recreated in Tableau by Jeffrey Shaffer [here]((https://www.bbc.com/news/world-62824357.amp)](https://public.tableau.com/app/profile/jeffrey.shaffer/viz/GapminderbyHansRosling/RoslingGapminder)). My thinking was this would allow me to still deliver the main message of the original visual - HDI decreased globally during 2020 for the first time - while also conveying a few other points they discussed in the BBC article. This included the idea that this decline was largely driven by changes in life expectancy during 2020 and that roughly 9/10 of countries experienced a decline that year (Hegarty, 2022). I tested a few color options before landing on the following color scheme, which categorizes countries according to whether they improved HDI, declined, or stayed the same relative to their previous year's HDI. This included testing out color coding based on region (Subsaharan Africa, MENA, South Asia, East Asia and Pacific, Latin America and the Caribbean, North America, Western Europe, Eastern Europe and Central Asia) which I immediately noted had too many color categories unless we aggregated regions further, such as into Northern/Southern Hemisphere or "Western" and "Eastern" countries. Even when collapsing categories and working with fewer, this didn't really add anything to the visual. I also tested coloring them based on GDP per capita to further encode more data and show how higher income countries tend towards higher HDI. This didn't really add much either, and muddied the more important message - in 2020 and 2021, many countries declined. 

Sketch #1

<div class='tableauPlaceholder' id='viz1731192267897' style='position: relative'><noscript><a href='#'><img alt='Preliminary Sketch #1Human Development Index (HDI) by Country - 2004The HDI of most countries increases from year to year, with the exception of 2020 and 2021, when 9 out of 10 countries saw their HDI decrease.  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDCritiquebyDesign&#47;HDIShowingRelativeImprovement&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWDCritiquebyDesign&#47;HDIShowingRelativeImprovement' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDCritiquebyDesign&#47;HDIShowingRelativeImprovement&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>         
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1731192267897');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

I developed the second option after very preliminary testing of the first led my initial reviewer to the same option I had considered in my critique as well - why isn't this a map? This allowed me to show regional trends without having to build this in as a color scheme or shape element, and I felt had greater perceptibility as well. Everyone instinctively knows that a map can show regional as well as global trends. 

Sketch #2

<div class='tableauPlaceholder' id='viz1731190159565' style='position: relative'><noscript><a href='#'><img alt='Preliminary Sketch #2Change in Human Development Index (HDI) by Country - 1991In 2020, the HDI decreased in 90% of countries due to COVID-19. Some regions were quicker to recover in 2021. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDCritiquebyDesign&#47;MapOption1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWDCritiquebyDesign&#47;MapOption1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDCritiquebyDesign&#47;MapOption1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1731190159565');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Step four: Test the solution(s)

I ended up conducting two rounds of testing, one for my first sketch and another for the second sketch. One reviewer provided feedback on both sketches; another provided feedback just on the final sketch of the map. 

**Feedback on Sketch 1**

Interview #1 (individual in late 20s with graduate degree and experience in international development):

1. The individual immediately asked what the actual definition of HDI was. I had yet to include a caption in my sketch as I had recommended based on my critique, and this solidified for me that this was necessary information.

2. Their key takeaways were consistent with my goal to showcase that HDI overall declined in 2020 and that life expectancy also declined. That being said, they noted that they wish they would have been able to examine regional trends and the countries in more detail. While I had included the minimum and maximum - and they did intuitively understand that is what those labels were - they noted this wasn't enough information for them.
   
3. When asked what was confusing, they shared that including life expectancy was confusing. Since that is part of how the UN calculates HDI, it is obviously connected to changing HDI values.
   
4. When asked what they would change, they noted the following:
   -It was difficult to tell what year it was as they clicked through the visual. They suggested making the year in the title more prominent or overlaying it on the visual somehow.
   -They did not like the subtitle using the "9 out of 10" language, which I had pulled from the BBC article. They fet that this might convey to some people that the visual only tracked 10 countries, when it clearly trackes more. They suggested using language like "90%" instead.
   -They liked the labels for the highest and lowest HDI each year, but wished they had been able to see more regional trends. They suggested testing color coding by region.
   -They noted that the data was not broken out enough for them to draw any surprising conclusions beyond the main two messages. Although there were dots representing each country, this really fared similar to an overall global trendline. 

**Feedback on Sketch 2**

Interview #2 (Individual in late 60's with graduate degree, no experience in international development): 

1. The very first thing this individual searched for and mentioned was also the definition of HDI. Upon reading the title, they said "but what's HDI?" and then immediately said "oh it's there at the bottom!". Again, encouraging sign that this caption is necessary and not superfluous.

2. They liked that they could explore changes over the years and across regions, and that they could click on different countries and see various statistics. They noted - without prompting - that they liked this level of detail better than a visualization that tried to show trends at a global scale, because they noticed so much variation between countries.
   
3. When asked about the key takeaways, they suggested that "HDI changes in different regions in different years, sometimes increasing and sometimes decreasing." This helped me identify that there are a lot of pages to click through, and that they had not even made it to 2019-2021 before they stopped interacting with the visually. While initially, I set the map to start at 1991 as the first timepoint so the reader could progress through history, this made me rethink this strategy. Some readers are not going to interact with the visual past the first glance, and certainly won't click through 30 pages of the visual. I made a note to try switching the start page to 2020, so at least the reader walks away with that snapshot if nothing else. Once I prompted them to click through each page, they then said "oh wow COVID was a huge change!", so the visual did communicate this... just not quickly enough. 

4. When asked what they would change, they did not have any suggestions. They liked the visual even more after they were able to see the effects of COVID, because it left them with another thought - while there were regional or country-level trends prior to COVID, COVID really dramatically impacted the world's HDI to a level that had not been seen before. 


Interview #3 (individual in late 20s with graduate degree):

Because this individual had already seen the first sketch, I adapted my questions somewhat for this interview to focus on where they still saw room for improvement and what they potentially liked better or worse. 

1. When asked what they liked about this sketch, they immediately noted that they felt the map was a much more effective visual than the previous sketch. Now they could see regional trends and global trends clearly, and it was much more intuitive. They liked the addition of the caption and the changes made to the title.
   
2. When asked what they did not like, they immediately mentioned the color scheme. They suggested there wasn't a ton of gradation - limiting the colors to three categories meant it was difficult to tell whether a country declined in HDI but only had a small decline versus had a large decline, for example. It also wasn't as aesthetically pleasing to them because of the very contrasting colors, and they worried that it may not be colorblind accessible.
   
3. When asked what they would change, they focused on the color scheme. They thought this was largely a great visual, but a few tweaks to the color could make it more powerful.
    

Clear takeaways:

1. A caption including the HDI is important! I should definitely include this in my final sketch, and maybe even consider moving the definition up to the subtitle since everyone immediately looked for it.

2. The map is more powerful than the gapminder-esque visual. Both reviewers were searching for regional and country-level information, and the more effective way to encode that was by just using a map (which makes logical sense).

3. Focus on the first look. I was thrilled with how startling 2020 was on the map in comparison to the previous ~30 some years, but forgot that lots of people won't click through far enough to make it to that point. Watching reviewer #2 interact with the map in real time (particularly as they are not the most tech-savvy person in the world), I was reminded that some people won't click through at all, either because they don't know they can or because they aren't interested enough to do so. If COVID-19 was the main message, it should start first.

4. Think through what data are necessary. Life expectancy was not - that seemed redundant and obvious to reviewer #1. But more gradation on country-level change was of interest. 

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1731189364983' style='position: relative'><noscript><a href='#'><img alt='Percent Change in Human Development Index (HDI) by Country - 2020In 2020, the HDI decreased in 90% of countries due to COVID-19. Some regions were quicker to recover in 2021. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDCritiquebyDesign&#47;MapOption2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWDCritiquebyDesign&#47;MapOption2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDCritiquebyDesign&#47;MapOption2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1731189364983');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                  
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


