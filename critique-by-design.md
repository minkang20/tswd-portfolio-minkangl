| [home page](README.md)| [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Meat Production in Germany 

In this project, I make a critical evaluation and iterative redesign of Meat Production in Germany to better communicate the underlying trends and narratives. 

## Step one: selection of the data visualization

I chose a work from MakeoverMonday, presented by the Federal Statistical Office of Germany, titled [Meat Production in Germany](https://www.destatis.de/EN/Press/2023/02/PE23_051_413.html). At first glance, the graph offers a simplistic and clear visualization of the trends in Germany's meat production changes. The use of colors and lines creates a minimalistic appeal. However, upon closer examination, I noticed some confusion. Although the title indicates a fall in meat production, this isn't immediately apparent from the graph's structural presentation.

Data link: [Meat Production in Germany](https://data.world/makeovermonday/2023w10)

## Step two: critique the data visualization

I completed a Google Form to analyze the data visualization thoroughly. In essence, the data visualization uses a line plot to display changes in poultry (growth), pork (fluctuation), and beef (decline) production trends since 2000, showing structural shifts in meat production. It faces clarity issues, particularly with the y-axis labels and the overall conveyance of the 8.1% decline in meat production mentioned in the title. The baseline year and numerical data are not adequately explained, which may confuse the primary audience of policymakers and microeconomics enthusiasts. To improve, the visualization should clarify labels and the y-axis, and include numerical data to better communicate specific trends. Despite its aesthetic appeal, the visualization's minimalistic approach and unclear messaging limit its effectiveness, particularly in providing context and a direct representation of the mentioned decrease in meat production. Recommendations include clearer legends, axes, and labels, alongside the integration of actual values to enhance understanding and communication of the data.

## Step three: sketch out a solution

<div class='tableauPlaceholder' id='viz1707242938782' style='position: relative'><noscript><a href='#'><img alt='Meat Production in Germany, 2000 - 2022Meat production down 8.1% in 2022 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;me&#47;meatproductioningermanydemo&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='meatproductioningermanydemo&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;me&#47;meatproductioningermanydemo&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707242938782');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

In  response, I drafted a solution employing a stacked area graph to more clearly depict the change in total production, aligning with the title and the content of the passage. This alternative visualization aims to make the recent downward trend more discernible to the audience. Additionally, I proposed modifications to the y-axis to minimize confusion, suggesting the year 2000 as the base.

## Step four: test the solution

I sought feedback from two friends—an engineer in their mid-20s and a finance major student in their early 20s—by showing them the work and asking a few targeted questions to see if my draft solution effectively conveyed the intended message. The questions included: "Can you tell me what this is about?" "Is there anything you find surprising or confusing?" and "Would you change anything or do differently?"

The summary of their responses indicated that both understood the plot to be about the change in meat production in Germany, easily inferred from the titles and legends. They also recognized the dynamics of the total production from the top of the stacked area. However, the engineer mentioned difficulties in comparing trends, especially for the top two categories, and could only ascertain a general increase in the bottom category. Despite the focus on total production, the original plot also aimed to highlight structural changes—a nuance I may have overlooked. The finance student suggested adding an additional line to represent the combined weight of the three categories for clearer comparison.

## Step five: my final solution and summary 


<div class='tableauPlaceholder' id='viz1707237488249' style='position: relative'><noscript><a href='#'><img alt='Meat Production in Germany: 2000-2022Production Declines by 8.1% in 2022, Continuing a Downward Trend Since 2016 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;me&#47;meatproductioningermanyfinal&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='meatproductioningermanyfinal&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;me&#47;meatproductioningermanyfinal&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707237488249');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Summary: 
Incorporating this feedback, I redesigned my sketch with three significant adjustments to the original work:

1. **Integration of an Additional Line:** Moving away from the stacked area plot, I introduced an extra line to the original plot with a separate y-axis for clarity. The use of distinct line styles—one solid and one dashed—helps differentiate between the structural change and the total production.
2. **Introduction of a Vertical Reference Line:** A vertical line was added to mark 2016 as the peak year for total production, assisting viewers in visually identifying the subsequent downward trend, complementing the narrative provided in the text.
3. **Refinement of Visualization Details:** Minor adjustments, such as modifying the y-axis, legends, and axis range, were made to alleviate confusion and enhance the visual appeal of the graph.

Through these revisions, I aimed to create a more intuitive and informative visualization that accurately represents the changes in Germany's meat production.



