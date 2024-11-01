| [home page](https://sarah1giordano.github.io/Giordano-Data-Viz/) | [visualizing government debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment 2: Visualizing Government Debt
## Part one: Working with web-based visualization tools and data

Below is an example visualization from OECD of government debt. OECD's data repository includes different indicators and interactive ways to view the data. These data were found by searching for "government debt," and choosing their general government debt dataset. I was able to choose specific years of data, and chose 2022; the column highlighted in blue is OECD's average country for comparison. 

<img src="Government Debt OECD.png.png" width="600"/>

[Source](https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2022&oecdcontrol-0b0bb95ebb-var1=OECD_REP%7CCAN%7CCHL%7CCOL%7CCRI%7CMEX%7CUSA%7CGBR%7CTUR%7CCHE%7CSWE%7CESP%7CSVN%7CSVK%7CPRT%7CPOL%7CNOR%7CNZL%7CNLD%7CLUX%7CLTU%7CLVA%7CKOR%7CJPN%7CITA%7CISR%7CIRL%7CISL%7CHUN%7CGRC%7CDEU%7CFRA%7CFIN%7CEST%7CDNK%7CCZE%7CBEL%7CAUT%7CAUS)


## Working with Tableau

The following visualization draws upon the same data from OECD on national debt to GDP ratio but visualizes it as a heat map instead, and shows how government debt has changed over time across countries. I created this visual using Tableau and following specific course instructions.

<div class='tableauPlaceholder' id='viz1730429999806' style='position: relative'><noscript><a href='#'><img alt='Japan&#39;s national debt is highest on averagecompared to national GDP over time ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Na&#47;NationalDebttoGDP&#47;NationalDebttoGDP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NationalDebttoGDP&#47;NationalDebttoGDP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Na&#47;NationalDebttoGDP&#47;NationalDebttoGDP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730429999806');                  
  var vizElement = divElement.getElementsByTagName('object')[0];                   
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

[Source](https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2022&oecdcontrol-0b0bb95ebb-var1=OECD_REP%7CCAN%7CCHL%7CCOL%7CCRI%7CMEX%7CUSA%7CGBR%7CTUR%7CCHE%7CSWE%7CESP%7CSVN%7CSVK%7CPRT%7CPOL%7CNOR%7CNZL%7CNLD%7CLUX%7CLTU%7CLVA%7CKOR%7CJPN%7CITA%7CISR%7CIRL%7CISL%7CHUN%7CGRC%7CDEU%7CFRA%7CFIN%7CEST%7CDNK%7CCZE%7CBEL%7CAUT%7CAUS)

## Part three: create your own visualization

I created the following visual using Tableau to help visualize the extent to which Japan's national debt to GDP ratio is an outlier, even among countries with high debt to GDP ratios. I played around with the data quite a bit before settling on this idea. While there are a number of stories I could have told -- different regional trends, countries that actually managed to decrease their national debt to GDP ratio, countries with huge changes in their ratios -- I found that this was one of the clearest to visualize. Japan also had high quality data in our dataset; by that, I mean OECD had data for Japan at every time period of interest, so there weren't gaps in the data. 

To showcase Japan's particularly high national debt to GDP ratio, I considered two main options: a bar chart or a line chart. The clearest way to visualize the gap between Japan and the next closest country (Greece) using a bar chart would have required me to select one point in time only. While I found this to be effective, when I tested out a line chart, I found it to be even more effective because it was able to still clearly convey that gap, but now showed that it has existed for ~20 years. While the bar chart lost almost all nuance in the data, the line chart was able to quickly convey the key idea (Japan is much higher than everyone else), while also including ideas such as:
    1) This is not recent, Japan has had the highest debt ratio since at least 2000 and crossed the 200% debt ratio in roughly 2010
    2) Japan has remained above the 200% threshold since then
    3) No country has even come close to joining them in crossing the 200% threshold until 2018
    4) If we expect Greece's ratio to increase at a roughly similar rate, they will join Japan in crossing this threshold and being one of the few high debt/GDP ratio countries to continue to increase that ratio, rather than decrease it or hold it steady



<div class='tableauPlaceholder' id='viz1730479334343' style='position: relative'><noscript><a href='#'><img alt='Japan is the only country with debt that exceeds 200% of national GDPbut Greece is close to joining the club. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtVisualization-Japancrosses200&#47;JapanVisualization&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebtVisualization-Japancrosses200&#47;JapanVisualization' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtVisualization-Japancrosses200&#47;JapanVisualization&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730479334343');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

[Source](https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2022&oecdcontrol-0b0bb95ebb-var1=OECD_REP%7CCAN%7CCHL%7CCOL%7CCRI%7CMEX%7CUSA%7CGBR%7CTUR%7CCHE%7CSWE%7CESP%7CSVN%7CSVK%7CPRT%7CPOL%7CNOR%7CNZL%7CNLD%7CLUX%7CLTU%7CLVA%7CKOR%7CJPN%7CITA%7CISR%7CIRL%7CISL%7CHUN%7CGRC%7CDEU%7CFRA%7CFIN%7CEST%7CDNK%7CCZE%7CBEL%7CAUT%7CAUS)

This visualize does, however, lose some nuance compared to the heat map from part 2. For one, keeping all the countries in the visual proved to be too much clutter. To deal with this, I chose to work with only a subset of the data: the countries with the.....

-Sarah talk about: time choice, country choice, eliminating those without all data, and go back and switch tick marks on x to every 2 years


Finally, use Markdown to write a paragraph or two about your thoughts on the different methods of visualization, and how they compare / contrast to one another. Make sure you include all source information and explain the data well.  Talk about why you chose the third data visualization.  It doesn't mean the last choice has to be necessarily better than the previous two, but I want to hear about why you chose it and what you were hoping it would show. 

_It's a good idea to go back and review your work.  Could someone follow your process and understand what you did?  Do you need to further connect any of the sections with a bit of text?  Is it something you'd be happy to have as an example of your work from the class?_



