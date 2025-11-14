| [home page](https://mblak3y.github.io/test-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Money, Money, Money: Budget vs Profit for the Marvel Cinematic Universe



## Step one: the visualization

Link to the Visualization: (https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/)

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

Respondent 1 — MSPPM Data Analytics (1st Year), Not a Marvel Fan, Extensive Data Viz Experience
Interviewer: Can you tell me what you think this is?
Respondent 1: At first glance, I thought this was a timeline of Marvel movies arranged by their overall profits. The structure made me assume the bars were meant to show some kind of progression over time. However, it wasn’t immediately obvious how the values were being organized.
Interviewer: Can you describe what this is telling you?
Respondent 1: I honestly couldn’t parse out what the visualization was trying to communicate because the information felt cluttered. The stacking of budget and gross made it difficult to distinguish the relative significance of each value. Overall, the organization didn’t guide my attention in a meaningful way.
Interviewer: Is there anything you find surprising or confusing?
Respondent 1: I wouldn’t say it was confusing—more that it lacked clarity. I could tell what the dataset was, but the presentation didn’t support quick interpretation. Nothing about the layout or content really surprised me given the context.
Interviewer: Who do you think is the intended audience for this?
Respondent 1: This definitely appears targeted toward Marvel fans who want a general sense of movie performance. It doesn’t seem optimized for someone with a data background or someone looking for analytical insights. The visual choices suggest an emphasis on entertainment rather than precision.
Interviewer: Is there anything you would change or do differently?
Respondent 1: I’d reorganize the graph so the hierarchy of information is clearer—stronger labeling, consistent spacing, and fewer competing visual elements. Separating the budget and gross into distinct visuals might help reduce information overload. 


Respondent 2 — MSPPM Flagship (1st Year), Moderate Marvel Fan, Medium Data Experience
Interviewer: Can you tell me what you think this is?
Respondent 2: It looks like a bar graph comparing the budgets and total earnings of different Marvel movies. My initial assumption was that the bars were meant to show which films performed the best financially. It took a moment to orient myself, but the theme was familiar enough.
Interviewer: Can you describe what this is telling you?
Respondent 2: I think it’s trying to highlight the relationship between how much each movie cost and how much revenue it brought in. You can see the variation across films, but there’s a lot happening visually. It ultimately communicates financial performance, though not in the clearest way.
Interviewer: Is there anything you find surprising or confusing?
Respondent 2: The original graph felt overwhelming because of how many dots and labels were packed into one space. Having the full movie titles directly next to each dot added unnecessary clutter. It took extra effort to separate meaningful information from the visual noise.
Interviewer: Who do you think is the intended audience for this?
Respondent 2: It seems aimed at casual Marvel fans who might enjoy seeing the financial side of the franchise but don’t necessarily need a deep analysis. The design feels more like something you’d encounter on a fan site rather than a technical report. It’s visually interesting but not analytically focused.
Interviewer: Is there anything you would change or do differently?
Respondent 2: I didn’t find the either graphic very useful for comparing data across films, so I’d streamline the presentation. I’d also consider grouping films in a more intuitive way—something tied to phases, characters, or release periods.



Respondent 3 — MSPPM Flagship (1st Year), Familiar Marvel, Extensive Data Experience
Interviewer: Can you tell me what you think this is?
Respondent 3: This looks like an attempt to visualize Marvel film budgets and earnings using a coordinate-plane-style layout. The structure implies comparisons across multiple films, but the setup initially felt more complex than necessary. I recognized the data type immediately, even though I’m not a Marvel follower.
Interviewer: Can you describe what this is telling you?
Respondent 3: It appears to show the financial performance of each film, but the axes unintentionally created quadrant implications that led me to search for meaning that wasn’t actually there. I found myself trying to interpret the positioning of films as if the quadrants represented categories or outcomes. Once I realized it wasn’t intentional, the purpose became clearer.
Interviewer: Is there anything you find surprising or confusing?
Respondent 3: The main confusion came from the stacked format—it took a moment to understand that the heights were cumulative rather than separate. 
Interviewer: Who do you think is the intended audience for this?
Respondent 3: It seems targeted toward Marvel fans who enjoy comparing films, not people seeking advanced insights. The simplicity of the bar graph suggests it's designed for casual browsing.


Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution


With my edited graph, I wanted to simplify it specifically to address how overwhelming the amount of information present on the original graph was. So, for this assignment, I decided to just focus specifically on capturing the relationship between the amount of money spent on the movie and the amount of money that it actually earned. I also additionally decided to focus on it by character and by phase within the MCU universe. I did this because I wanted this graphic to be catered towards casual moviegoers—people without backgrounds in data analytics—and people typically go to movies based off of characters that they are attracted to. So I figured organizing the data in this way would be relevant and appealing to the audience.

I also wanted to remove one of the axes on the graph because, as I’ll get into later, when I looked at the original visualization I thought of it as a coordinate plane, and I interpreted it specifically as having three quadrants. On my initial intake, I thought that it would make sense for movies to want to be in the third quadrant, which would indicate that there is a positive value for both of the coordinates being used. I decided to use bar graphs because, again, I'm targeting the casual moviegoer, and bar graphs really show and capture the relationship specifically by group. With that group, I grouped them by different phases within the MCU universe.
Additionally, I also changed the labels on the graphs. In removing the axes, I combined the title and the year that the movie was released, which I thought would be useful for the different characters that I was using for the MCU universe. Given that I was organizing them by character and phase within the universe, having the year next to the title of the movie would help aid with temporal organization.

As you saw on the first graph, Endgame and Infinity War repeatedly extend far beyond the scale of the other films. I built the categories to group the movies by the main characters or franchises, and those two films consistently distorted the image. They dominated the visual in a way that didn’t add meaningful insight, so I ultimately removed them to allow the other data to be interpreted more clearly. I decided instead to focus on the different phases of the MCU because I felt that this structure better captured the evolution and strategic development of Marvel’s cinematic storytelling. The phases also reflect Marvel’s long-term marketing strategy and the sequencing of film releases. Over time, these phases demonstrate how Marvel used a “blue ocean strategy”—identifying an underdeveloped niche within action and superhero films and then expanding it into a massive, interconnected universe. I also thought it was interesting how each film builds toward the next through end-credit scenes, functioning almost like narrative “Easter eggs” that guide viewers through the larger universe. Organizing the data by phase made it easier to see how the MCU grew, how audiences responded at different points in the timeline, and how Marvel’s strategies shaped the overall success of the franchise


Final Solution

<img width="2796" height="2548" alt="93WLF-money-money-money-nbsp-budgets-vs-worldwide-gross-in-mcu-films-by-phase-" src="https://github.com/user-attachments/assets/c16834c5-f104-48c9-9176-cf654f625988" />



## References
_List any references you used here._

## AI acknowledgements
I did not use AI for this assignment

