| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing government debt](visualizing-government-debt) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique By Design
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

## Step one: the visualization

This visualization was selected from [MakeoverMonday's](https://makeovermonday.co.uk/) weekly series, which encourages people to hone their data visualization skills through redesign. The webpage by the National Oceanic and Atmospheric Adminstration seeks to communicate scientific measures of climate change to a more general audience, such as policy makers. This issue is of particular interest to me, as I am interested in better understanding the imapcts of climate on culutral institutions, and the role they play in educating the public about climate. This type of information could be used withing a museum setting - further interpreted for a general audience. 

The first graphic shows global average 

<img src="NOAA-GHG Abundance.png" width="800">

**Figure 1:** 

**Source:** The NOAA Annual Greenhouse Gas Index (AGGI). National Oceanic and Atmospheric Administration. 2024. https://gml.noaa.gov/aggi/aggi.html

<img src="Radiative Forcing.png" width="800">

**Figure 2:**

**Source:** The NOAA Annual Greenhouse Gas Index (AGGI). National Oceanic and Atmospheric Administration. 2024. https://gml.noaa.gov/aggi/aggi.html 


## Step two: the critique
Note: I conducted my initial critique with a focus on Figure 1.  Using their data set, the chart I ultimatley sketched shared more similar elements with a different visualization on the NOAA webpage, so I have included both for the purposes of this analysis. 

The data visualization is useful, though only in telling a fairly limited story. It takes a little bit of digging to see exactly what the charts are showing - you see that it’s a level of these Greenhouses gases, but it’s not immediately clear if this is showing emissions for a specific country or region, levels in the atmosphere, etc. 

A clear title describing what the audience should take away would improve this. After reading the description, I discovered that it shows global greenhouse gas abundance for Carbon Dioxide, Nitrous Oxide, Methane, and other gases. From these charts, it’s easy to see in general, they each increase over time. However, it is extremely difficult to compare trends between gases, as each has an extremely different scale (parts per million vs. billion vs. trillion). If each chart was isolated, this scaling may be useful to make data points clear and visible and wouldn’t cause much concern. However, by displaying them together in this, this is likely to mislead the viewer to believe that these gases exist at a similar level. In terms of color, there are a number of opportunities to enhance the visualization.  the same color is used across the four charts to represent different gases, which could also lead to confusion in interpreting that chart. Aesthetically, this visualization does not effectively attract or engage more attention. could be improved by reducing alignment points.

Figure 2 works to address some of these issues. First, gases are made proportional by multiplying the quantity of abundance by a factor representing its warming potential. This makes it easier. 


## Step three: Sketch a solution

<img src="NOAA-GHG Abundance.png" width="800">



## Step four: Test the solution

To better understand how this sketch would be interpreted by general uses, I tested the sketch with peers. The goal was to see how they interpreted the visualization with limited context and identify opportunities to strengthen the design. Three students from the Heinz College of Information Systems and Public Policy reviewed the sketch and responded to the following prompts: 

- Can you describe what this is telling you?
- Is there anything you find confusing?
- Is there anything you would change or do differently?

**Results:** 

| Question | Interview 1 | Interview 2 | Interview 3 | 
|----------|-------------|-------------|------------|
|Can you describe what this is telling you?  | Greenhouse Gas Emissions | Changes in Emissions Over Time | 
|Is there anything you find confusing?  | Which gas is focus?  | Difficult to see differences in proportion | Meaning of measurements used. 
|Is there anything you would change or do differently?  | Reduce Colors; Use alert color   | Consider bar chart or tree map to show proportions | Enhance title and axis descriptions

**Synthesis:** 

A couple key themes emerged from this feedback - first, that there is opportunity to more clearly articlulate one key story from this visualization. While respondants saw value in this type of chart in showing proportion and changes over time, it was difficult to get a clear understanding differences in proportion, or how they may change over time. This is a known risk of using stacked area graphs, but there are additional design elements that might better. As I move into the final design, I plan to incorporate the following design changes: 

- Focus "story" on Carbon Dioxide (CO2) 
- Use red as an alert color to call attention to Carbon Dioxide on the graph
- Group CFC's and HFC's as "other gases" to reduce number of elements
- Label axes clearly to communicate meaning of measurements
- Use a descriptive title to quickly convey the meaning of the chart

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

<img src="NOAA-GHG Abundance.png" width="800">

## References
"Improving How We Visualize and Analyze Data." MakeoverMonday. Accessed February 7, 2024. [https://makeovermonday.co.uk/](https://makeovermonday.co.uk/)

"The NOAA Annual Greenhouse Gas Index." Global Monitoring Laboratory, National Oceanic and Atmostpheric Administration. 2024. [https://gml.noaa.gov/aggi/aggi.html](https://gml.noaa.gov/aggi/aggi.html)

