# Critique By Design
## Part 1: Data Visualization with Reference Data

For this assignment, I chose the data visualization below from the [article](http://howmuch.net/articles/trade-war-in-6-visualizations). The primary objective of this article is to convey through different data visualizations how the US-China trade war has impacted the health of both economies and brought fear to the global markets. 

This data visualization reflects the Foreign Exchange Reserves of different countries for Q1, 2018. I chose this visualization because of three reasons:
1. Foreign Exchange Reserves are regarded as the health meter of any country, and include assets such as foreign currencies, gold reserves, treasury bills etc. that are retained by the central bank or other federal monetary authority. 
2. The visualization does not support the main premise of the article since it does not provide any trends for comparison but only offers a snapshot view of this economic indicator for one quarter.
3. The graphic does does not follow principles of good design and has room for improvement across several elements, if evaluated on the heuristics model.

Reference data for foreign exchange reserves of different countries across several years was retrieved using the World Bank's [Data Repository](http://data.worldbank.org/indicator/FI.RES.XGLD.CD).

<iframe width="800" height="600" src="https://cdn.howmuch.net/articles/the-forex-worldmap-final-8322.jpg"></iframe>

## Part 3: Wireframe a Solution

I tried using the tool [Balsamiq](http://balsamiq.com/) to draft my thought process. Considering the type of data, I decided to use another visualization type to redesign the map above based on the issues identified in the critique method. I first considered using either a bar or a line chart below, but decided to sketch only the line chart due to the limitations identified with bar charts in representing this data, primarily the absence of historical trends. 

![image](https://user-images.githubusercontent.com/93225948/140595253-8f119be3-1cc9-4ca5-b15b-147070cbc763.png)
![image](https://user-images.githubusercontent.com/93225948/140595176-3e15acfe-4b1d-4421-ac98-dbd544f7fcde.png)
![image](https://user-images.githubusercontent.com/93225948/140595199-5c3868e0-f189-40e7-b638-9217ac730655.png)
![image](https://user-images.githubusercontent.com/93225948/140595204-038a58ce-b867-4436-aae1-5667eeccc677.png)

## Part 4: Test the Solution 

I showed the wireframe to two individuals: my spouse, considering her academic background in Political Science and another peer at Carnegie Mellon University. Responses from each individual are mentioned under the questions.

**Can you tell me what you think this is?**
1. _"A line chart depicting the FOREX reserves of major countries over a period of time."_
2. _"Change in Forex reserves over the years for different countries."_

**Can you describe to me what this is telling you?**
1. _"While drawing comparison between the countries that have the highest FOREX reserves in their regions, the graph highlights how much greater China's reserves are compared to the rest of the world."_
2. _"Before and after-effects of US-China trade wars on Forex reserve."_

**Is there anything you find surprising or confusing?**
1. _"From 2019-2020, all countries seem to have either a relatively steady or increasing FOREX reserves. The United States' reserves are much lower than those of China's."_
2. _"Seeing same color for Japan and China got me confused. At first, I thought these are different colors and I am not looking at them properly but realized from the key that you have clubbed colors as per region."_

**Who do you think is the intended audience for this?**
1. _"The audience is most likely governments, or  independent entities, such as the World Bank Group or International Monetary Fund, who could utilize this visualization."_
2. _"Those who have some knowledge of the war and how it can possibly affect forex rates so definitely an audience that has some background knowledge on international affairs and political economies."_

**Is there anything you would change or do differently?**
1. _"There seems to be a lot of clutter with the lines and labels on the graph. Perhaps this is a problem with the prototype and if drawn to scale with more space, it would be less of a strain for the audience to draw conclusions. If the top 3 countries are shown from each region of the world together, this type of visualization might fail to convey any insight."_
2. _"Introduce a print version (black and white version) for this graph. Colors can be deceiving in print versions (and even for audiences suffering with some form of color-blindness) so adding different symbols for each curve data point might be a better idea."_

## Part 5: Build Your Solution

### Written Summary
Stephen Few's Critique Method allowed me to disassemble the visualization into crucial elements and examine each individually. Critique components such as _truthfulness_ made me consider ways in which the original visualization type could be problematic in presenting this data accurately. Moreover, thinking about the audience helped me refine my perspective before approaching the redesign phase, as I could screen out unnecessary details from my rudimentary thoughts and instead look for _completeness_ within the identified context. To summarize, the critique made me think about how to align my visualization with the audience expectations by incorporating more data such as year on year trends, and filtering out trivial information while redesigning by narrowing down to top perofrming countries within each region. 

The wireframes helped me map my thought process, understand the type of data available and evaluate the pros & cons of few visualization types. The user feedback based on the wireframe and redesign sketch allowed me to gain some confidence regarding my understanding of the intended audience. However, at the same time it showed me how the presence of clutter and disregard for the use of color blind safe palettes required rework. Moreover, it felt like the key assigning same colors to each region had little contribution in aiding user perceptibility, challenging my original thoughts in the critique. The premise of the article revolved around the US-China trade war, but it wasn't quite evident to the users here, which made me want to reinforce this idea in my final visualization. Except the suggestion to change shapes, I tried to address these concerns in the graphic below. 

For my final visualization below, I had to rework the data to show a line chart that could help identify a trend over the years, 2011 to 2020. With a broad enough time horizon, the audience would be able to see whether Forex Reserves were in any way correlated with the US-China trade war. Instead of grouping countries based on regions, I decided to only show countries which had the highest Forex Reserves in their region (in addition to US and China). This was in line with insights from the critique and user feedback, aiming to make the graph look less busy, without compromising on its _completeness_. A red highlight on the x-axis allowed me to highlight the main event under question i.e. the US-China trade war and included a menu at the top for individuals who would solely be interested in a comparison between the US and China. I also used color blind safe palette for the lines and rephrased the title/ subtitle support the premise of the article.

<div class="flourish-embed flourish-chart" data-src="visualisation/7746600"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

In my wireframe, I highlighted a limitation of bar charts: an absence of trends over time. However, I was able to explore this animated bar chart which interestingly serves the purpose of easing comparison between countries and showing their progress over time. Although, I couldn't highlight the US-China Trade War as an event here, I still thought it would be a good addition to this portfolio!

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/7746758"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

