| [home page](https://mblak3y.github.io/test-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Money, Money, Money: Budget vs Profit for the Marvel Cinematic Universe



## Step one: the visualization

Link to the Visualization: 

https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/

<img width="2922" height="1508" alt="image" src="https://github.com/user-attachments/assets/aa91e9e7-ce64-4a8f-a9a5-6d5e163fd3f7" />


The visualization I selected is an interactive graphic from a movie website that shows relationships between different movie metrics, such as budget, percentage of budget recovered, critics’ score, audience score, and the deviation between critics’ and audience scores. The dataset is based on all 35 movies within the Marvel Cinematic Universe.

However, I chose this graphic because I was impressed by the volume of information captured using its interactive features. I like that the graph allows you to change the metrics on each axis. As shown at the bottom of the graphic, you can look at the actual budget, the percentage of budget recovered, audience ratings, critics’ ratings, and the deviations between the two. 



## Step two: the critique
The original visual plots all of this information on a coordinate plane, with axes that can be changed based on the metric. Personally, I found the image overwhelming. When I first encountered it, I actually scrolled past it because I thought it was a header, not the actual visualization. The black background made it hard to distinguish the boundaries of the graphic and the extent of the information being shown. The lack of background borders added to the confusion. 

Additionally, the visualization displays a large amount of information all at once. There are 35 movies within the Marvel Universe, and on first viewing, all 35 appear on the graph simultaneously. This makes it difficult to make meaningful comparisons between different franchises. As a moviegoer—the intended audience for the graphic—I typically think of Marvel films by the phases of the cinematic universe. Aside from using the release year, the graph does not allow viewers to sort or separate movies by phase, which limits the ability to identify distinctions between groups or make comparisons. I also found the use of the full movie titles cluttered and overwhelming. 

Still, in this presentation, everything appears together, and the viewer is not able to easily parse or distinguish between comparisons. Because of the overwhelming amount of information and limited ability to filter or group the data, I do not see this graph having much utility in analytical settings. Instead, it seems designed primarily to be interactive and visually engaging for website visitors, rather than to support deeper data analysis.


## Step three: Sketch a solution

<img width="2796" height="1946" alt="image" src="https://github.com/user-attachments/assets/c80e0cae-ba6f-48aa-86fb-912935872107" />


## Step four: Test the solution

Respondent 1

MSPPM Data Analytics (1st Year)
Not a Marvel Fan
Extensive Data Viz Experience

What do you think this is?

At first glance, I thought this was a timeline of Marvel movies arranged by their overall profits. The structure made me assume the bars were showing some kind of progression over time, but it wasn’t clear how the values were being organized.

What is this telling you?

I couldn’t parse out what the visualization was trying to communicate because the information felt cluttered. The stacking of budget and gross made it difficult to distinguish the significance of each value. The organization didn’t guide my attention in a meaningful way.

Anything surprising or confusing?

It wasn’t confusing—just unclear. I could tell what the dataset was, but the presentation didn’t support quick interpretation. Nothing in the layout was surprising given the context.

Who is the intended audience?

Likely Marvel fans who want a general sense of movie performance. It does not appear intended for someone with a data background or someone looking for analytical insights.

What would you change?

I’d reorganize the graph so the hierarchy of information is clearer—stronger labeling, consistent spacing, fewer competing visuals. Separating budget and gross into distinct visuals could reduce overload.

Respondent 2

MSPPM Flagship (1st Year)
Moderate Marvel Fan
Medium Data Experience

What do you think this is?

It looks like a bar graph comparing budgets and total earnings of Marvel movies. I assumed the bars showed financial performance, though it took a moment to orient myself.

What is this telling you?

It’s highlighting the relationship between how much each movie cost and how much revenue it generated. The variation across films is visible, but there’s a lot happening visually.

Anything surprising or confusing?

The original graph felt overwhelming because of the many dots and labels. Full movie titles next to each dot added clutter and made comparison difficult.

Who is the intended audience?

Casual Marvel fans who might enjoy financial comparisons but don’t need deep analysis. It feels more like fan-site content than a technical visualization.

What would you change?

I’d streamline the presentation and group films more intuitively—by phases, characters, or release periods.

Respondent 3

MSPPM Flagship (1st Year)
Familiar with Marvel
Extensive Data Experience

What do you think this is?

It looks like an attempt to visualize Marvel film budgets and earnings using a coordinate-plane style. The layout suggested comparisons across films but felt more complex than needed.

What is this telling you?

It shows financial performance, but the axes unintentionally created quadrant implications that made me search for meaning that wasn’t there. Once I realized the quadrants weren’t intentional, the purpose became clearer.

Anything surprising or confusing?

The stacked format caused some confusion—it took a moment to understand the heights were cumulative, not separate.

Who is the intended audience?

Marvel fans who enjoy comparing films. The bar chart’s simplicity signals it’s for casual viewing rather than analytical interpretation.




## Step five: Synthesis & build the solution

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Interactive Tableau Viz</title>
</head>
<body>

<h2>Interactive Tableau Visualization</h2>

<div class="tableauPlaceholder" id="viz1763095349175" style="position: relative;">
  <noscript>
    <a href="#">
      <img
        alt="Money, Money, Money: Budget vs Global Gross Profit for the Entire MCU Universe"
        src="https://public.tableau.com/static/images/Da/DataCritiqueOneFD/Sheet1/1.png"
        style="border: none;"
      />
    </a>
  </noscript>

  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F"/>
    <param name="embed_code_version" value="3"/>
    <param name="site_root" value=""/>
    <param name="name" value="DataCritiqueOneFD/Sheet1"/>
    <param name="tabs" value="no"/>
    <param name="toolbar" value="yes"/>
    <param name="static_image" value="https://public.tableau.com/static/images/Da/DataCritiqueOneFD/Sheet1/1.png"/>
    <param name="animate_transition" value="yes"/>
    <param name="display_static_image" value="yes"/>
    <param name="display_spinner" value="yes"/>
    <param name="display_overlay" value="yes"/>
    <param name="display_count" value="yes"/>
    <param name="language" value="en-US"/>
    <param name="filter" value="publish=yes"/>
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("viz1763095349175");
  var vizElement = divElement.getElementsByTagName("object")[0];
  vizElement.style.width = "100%";
  vizElement.style.height = (divElement.offsetWidth * 0.75) + "px";

  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

</body>
</html>



With my edited graph, I wanted to simplify it specifically to address how overwhelming the amount of information present on the original graph was. So, for this assignment, I decided to just focus specifically on capturing the relationship between the amount of money spent on the movie and the amount of money that it actually earned. I also additionally decided to sort by phase within the MCU universe. I did this because I wanted this graphic to be catered towards casual moviegoers. 

I also wanted to remove one of the axes on the graph because, as I’ll get into later, when I looked at the original visualization I thought of it as a coordinate plane, and I interpreted it specifically as having three quadrants. On my initial intake, I thought that it would make sense for movies to want to be in the third quadrant, which would indicate that there is a positive value for both of the coordinates being used. 


I decided instead to focus on the different phases of the MCU because I felt that this structure better captured the evolution and strategic development of Marvel’s cinematic storytelling. The phases also reflect Marvel’s long-term marketing strategy and the sequencing of film releases. 
With this assignment, I wanted to simplify the graph to show how the MCU profitability drastically increased with the phase released. I organized them this way because I wanted to capture  Marvel identified an underdeveloped niche within superhero action  films, expanded it into a massively interconnected univers, and maintained the dominance over time. I also thought it was interesting how each film builds toward the next through end-credit scenes, functioning almost like narrative “Easter eggs” that guide viewers through the larger universe. 

As I looked through the different phases and their subsequent titles, I was taken back to memories of being in the theaters and seeing how the trend of waiting until after the credit became common movie going practice. Organizing the data by phase made it easier to see how the MCU grew, how audiences responded at different points in the timeline, and how Marvel’s strategies shaped the overall success of the franchise

Ideally, an optimal version of the final solution would sort the graphs by release date and not increasing profit. 


Final Solution

<img width="2796" height="2548" alt="93WLF-money-money-money-nbsp-budgets-vs-worldwide-gross-in-mcu-films-by-phase-" src="https://github.com/user-attachments/assets/c16834c5-f104-48c9-9176-cf654f625988" />



## References

The Link to the Data and Original Visualization


https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/



## AI acknowledgements
I did not use AI for this assignment

